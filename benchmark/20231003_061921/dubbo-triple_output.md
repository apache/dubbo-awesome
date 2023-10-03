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
# Warmup Iteration   1: 1.426 ops/ms
# Warmup Iteration   2: 3.014 ops/ms
# Warmup Iteration   3: 6.517 ops/ms
Iteration   1: 7.125 ops/ms
Iteration   2: 7.757 ops/ms
Iteration   3: 7.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.500 ±(99.9%) 6.060 ops/ms [Average]
  (min, avg, max) = (7.125, 7.500, 7.757), stdev = 0.332
  CI (99.9%): [1.440, 13.560] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.065 ops/ms
# Warmup Iteration   2: 6.424 ops/ms
# Warmup Iteration   3: 7.659 ops/ms
Iteration   1: 8.129 ops/ms
Iteration   2: 8.213 ops/ms
Iteration   3: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.198 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (8.129, 8.198, 8.251), stdev = 0.062
  CI (99.9%): [7.062, 9.333] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 6.165 ops/ms
# Warmup Iteration   3: 7.538 ops/ms
Iteration   1: 7.584 ops/ms
Iteration   2: 7.584 ops/ms
Iteration   3: 7.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.585 ±(99.9%) 0.036 ops/ms [Average]
  (min, avg, max) = (7.584, 7.585, 7.588), stdev = 0.002
  CI (99.9%): [7.550, 7.621] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.936 ops/ms
# Warmup Iteration   2: 4.720 ops/ms
# Warmup Iteration   3: 6.126 ops/ms
Iteration   1: 6.027 ops/ms
Iteration   2: 6.272 ops/ms
Iteration   3: 6.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.284 ±(99.9%) 4.814 ops/ms [Average]
  (min, avg, max) = (6.027, 6.284, 6.554), stdev = 0.264
  CI (99.9%): [1.471, 11.098] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.652 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.882 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.488 ±(99.9%) 0.007 ms/op
Iteration   1: 4.211 ±(99.9%) 0.003 ms/op
Iteration   2: 4.216 ±(99.9%) 0.005 ms/op
Iteration   3: 3.989 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.139 ±(99.9%) 2.368 ms/op [Average]
  (min, avg, max) = (3.989, 4.139, 4.216), stdev = 0.130
  CI (99.9%): [1.770, 6.507] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.760 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.828 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.005 ms/op
Iteration   1: 3.912 ±(99.9%) 0.005 ms/op
Iteration   2: 4.153 ±(99.9%) 0.009 ms/op
Iteration   3: 4.078 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.048 ±(99.9%) 2.255 ms/op [Average]
  (min, avg, max) = (3.912, 4.048, 4.153), stdev = 0.124
  CI (99.9%): [1.792, 6.303] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.385 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.006 ms/op
Iteration   1: 4.168 ±(99.9%) 0.007 ms/op
Iteration   2: 4.159 ±(99.9%) 0.006 ms/op
Iteration   3: 4.023 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.117 ±(99.9%) 1.488 ms/op [Average]
  (min, avg, max) = (4.023, 4.117, 4.168), stdev = 0.082
  CI (99.9%): [2.629, 5.605] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 15.813 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.980 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.011 ±(99.9%) 0.007 ms/op
Iteration   1: 4.942 ±(99.9%) 0.010 ms/op
Iteration   2: 5.037 ±(99.9%) 0.008 ms/op
Iteration   3: 4.944 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.974 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (4.942, 4.974, 5.037), stdev = 0.055
  CI (99.9%): [3.978, 5.971] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.841 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.256 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.701 ±(99.9%) 0.022 ms/op
Iteration   1: 4.152 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  24.348 ms/op
                 createUser·p0.9999: 33.170 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   2: 4.036 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  14.991 ms/op
                 createUser·p0.9999: 27.364 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 4.228 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   9.634 ms/op
                 createUser·p0.999:  30.584 ms/op
                 createUser·p0.9999: 38.367 ms/op
                 createUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232063
  mean =      4.137 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 144 
    [ 2.500,  5.000) = 217670 
    [ 5.000,  7.500) = 10484 
    [ 7.500, 10.000) = 2512 
    [10.000, 12.500) = 788 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 39 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      8.624 ms/op
     p(99.9000) =     25.657 ms/op
     p(99.9900) =     33.803 ms/op
     p(99.9990) =     38.404 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.110 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
Iteration   1: 4.011 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.858 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.560 ms/op
                 existUser·p0.99:   7.881 ms/op
                 existUser·p0.999:  23.626 ms/op
                 existUser·p0.9999: 27.854 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   2: 3.832 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   7.163 ms/op
                 existUser·p0.999:  16.663 ms/op
                 existUser·p0.9999: 28.169 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   3: 4.031 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   8.217 ms/op
                 existUser·p0.999:  15.015 ms/op
                 existUser·p0.9999: 33.227 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242736
  mean =      3.956 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 370 
    [ 2.500,  5.000) = 229149 
    [ 5.000,  7.500) = 9516 
    [ 7.500, 10.000) = 2855 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     16.693 ms/op
     p(99.9900) =     31.946 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.882 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 5.103 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.302 ±(99.9%) 0.014 ms/op
Iteration   1: 4.116 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   8.651 ms/op
                 getUser·p0.999:  21.463 ms/op
                 getUser·p0.9999: 23.888 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 4.063 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.999 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  12.124 ms/op
                 getUser·p0.9999: 27.009 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 4.195 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.832 ms/op
                 getUser·p0.999:  12.399 ms/op
                 getUser·p0.9999: 29.045 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232697
  mean =      4.124 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 219328 
    [ 5.000,  7.500) = 10583 
    [ 7.500, 10.000) = 2046 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 13.828 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 6.375 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 4.892 ±(99.9%) 0.017 ms/op
Iteration   1: 4.762 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  25.482 ms/op
                 listUser·p0.9999: 27.937 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 4.941 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  18.982 ms/op
                 listUser·p0.9999: 28.169 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   3: 4.858 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   9.335 ms/op
                 listUser·p0.999:  19.192 ms/op
                 listUser·p0.9999: 23.804 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197729
  mean =      4.853 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 157705 
    [ 5.000,  7.500) = 34845 
    [ 7.500, 10.000) = 3814 
    [10.000, 12.500) = 682 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     22.696 ms/op
     p(99.9900) =     27.646 ms/op
     p(99.9990) =     28.606 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.500 ± 6.060  ops/ms
ClientPb.existUser                       thrpt       3   8.198 ± 1.135  ops/ms
ClientPb.getUser                         thrpt       3   7.585 ± 0.036  ops/ms
ClientPb.listUser                        thrpt       3   6.284 ± 4.814  ops/ms
ClientPb.createUser                       avgt       3   4.139 ± 2.368   ms/op
ClientPb.existUser                        avgt       3   4.048 ± 2.255   ms/op
ClientPb.getUser                          avgt       3   4.117 ± 1.488   ms/op
ClientPb.listUser                         avgt       3   4.974 ± 0.996   ms/op
ClientPb.createUser                     sample  232063   4.137 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.589           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.624           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.657           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.470           ms/op
ClientPb.existUser                      sample  242736   3.956 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.530           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.979           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.693           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.946           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  232697   4.124 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.892           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.807           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.037           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.886           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  197729   4.853 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.044           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.696           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.646           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606           ms/op
