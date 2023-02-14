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
# Warmup Iteration   1: 1.358 ops/ms
# Warmup Iteration   2: 3.688 ops/ms
# Warmup Iteration   3: 7.072 ops/ms
Iteration   1: 7.508 ops/ms
Iteration   2: 7.964 ops/ms
Iteration   3: 7.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.788 ±(99.9%) 4.484 ops/ms [Average]
  (min, avg, max) = (7.508, 7.788, 7.964), stdev = 0.246
  CI (99.9%): [3.305, 12.272] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.098 ops/ms
# Warmup Iteration   2: 6.150 ops/ms
# Warmup Iteration   3: 7.783 ops/ms
Iteration   1: 7.527 ops/ms
Iteration   2: 8.176 ops/ms
Iteration   3: 8.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.954 ±(99.9%) 6.752 ops/ms [Average]
  (min, avg, max) = (7.527, 7.954, 8.176), stdev = 0.370
  CI (99.9%): [1.203, 14.706] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.993 ops/ms
# Warmup Iteration   2: 6.033 ops/ms
# Warmup Iteration   3: 7.629 ops/ms
Iteration   1: 7.709 ops/ms
Iteration   2: 7.859 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.910 ±(99.9%) 4.201 ops/ms [Average]
  (min, avg, max) = (7.709, 7.910, 8.161), stdev = 0.230
  CI (99.9%): [3.708, 12.111] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.188 ops/ms
# Warmup Iteration   2: 5.717 ops/ms
# Warmup Iteration   3: 6.535 ops/ms
Iteration   1: 6.839 ops/ms
Iteration   2: 6.832 ops/ms
Iteration   3: 6.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.806 ±(99.9%) 0.950 ops/ms [Average]
  (min, avg, max) = (6.746, 6.806, 6.839), stdev = 0.052
  CI (99.9%): [5.855, 7.756] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.101 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.332 ±(99.9%) 0.009 ms/op
Iteration   1: 4.169 ±(99.9%) 0.004 ms/op
Iteration   2: 3.937 ±(99.9%) 0.005 ms/op
Iteration   3: 4.108 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.071 ±(99.9%) 2.193 ms/op [Average]
  (min, avg, max) = (3.937, 4.071, 4.169), stdev = 0.120
  CI (99.9%): [1.878, 6.264] (assumes normal distribution)


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
# Warmup Iteration   1: 13.585 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.994 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.007 ms/op
Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
Iteration   2: 3.796 ±(99.9%) 0.005 ms/op
Iteration   3: 3.876 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.839 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.796, 3.839, 3.876), stdev = 0.040
  CI (99.9%): [3.102, 4.577] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.329 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.725 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.501 ±(99.9%) 0.013 ms/op
Iteration   1: 4.014 ±(99.9%) 0.007 ms/op
Iteration   2: 4.008 ±(99.9%) 0.008 ms/op
Iteration   3: 4.090 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.037 ±(99.9%) 0.834 ms/op [Average]
  (min, avg, max) = (4.008, 4.037, 4.090), stdev = 0.046
  CI (99.9%): [3.203, 4.871] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.115 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.383 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.819 ±(99.9%) 0.009 ms/op
Iteration   1: 4.807 ±(99.9%) 0.009 ms/op
Iteration   2: 4.709 ±(99.9%) 0.012 ms/op
Iteration   3: 4.808 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.775 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (4.709, 4.775, 4.808), stdev = 0.057
  CI (99.9%): [3.740, 5.809] (assumes normal distribution)


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
# Warmup Iteration   1: 13.658 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 5.533 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.564 ±(99.9%) 0.020 ms/op
Iteration   1: 4.292 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.005 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   6.431 ms/op
                 createUser·p0.99:   8.520 ms/op
                 createUser·p0.999:  13.787 ms/op
                 createUser·p0.9999: 27.722 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 3.936 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   7.627 ms/op
                 createUser·p0.999:  25.856 ms/op
                 createUser·p0.9999: 29.257 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   3: 3.944 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.062 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  27.712 ms/op
                 createUser·p0.9999: 30.729 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237045
  mean =      4.051 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 165 
    [ 2.500,  5.000) = 221734 
    [ 5.000,  7.500) = 12261 
    [ 7.500, 10.000) = 2207 
    [10.000, 12.500) = 383 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 107 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     30.166 ms/op
     p(99.9990) =     31.536 ms/op
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
# Warmup Iteration   1: 12.875 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 5.042 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.012 ms/op
Iteration   1: 3.973 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.040 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 25.129 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 3.953 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   7.594 ms/op
                 existUser·p0.999:  24.835 ms/op
                 existUser·p0.9999: 27.394 ms/op
                 existUser·p1.00:   30.179 ms/op

Iteration   3: 3.927 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 36.297 ms/op
                 existUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243265
  mean =      3.951 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214 
    [ 2.500,  5.000) = 230806 
    [ 5.000,  7.500) = 10205 
    [ 7.500, 10.000) = 1509 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.735 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     15.642 ms/op
     p(99.9900) =     34.647 ms/op
     p(99.9990) =     37.233 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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
# Warmup Iteration   1: 13.811 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.815 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.012 ms/op
Iteration   1: 4.180 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  23.364 ms/op
                 getUser·p0.9999: 26.401 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   7.273 ms/op
                 getUser·p0.999:  15.647 ms/op
                 getUser·p0.9999: 28.514 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 4.069 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.130 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  27.951 ms/op
                 getUser·p0.9999: 36.635 ms/op
                 getUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234986
  mean =      4.084 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 220445 
    [ 5.000,  7.500) = 11584 
    [ 7.500, 10.000) = 2136 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     34.832 ms/op
     p(99.9990) =     37.025 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 14.916 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 5.661 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.884 ±(99.9%) 0.018 ms/op
Iteration   1: 4.926 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.624 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  25.657 ms/op
                 listUser·p0.9999: 29.753 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   2: 4.846 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  19.193 ms/op
                 listUser·p0.9999: 33.751 ms/op
                 listUser·p1.00:   34.406 ms/op

Iteration   3: 4.644 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  16.653 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200048
  mean =      4.802 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 160642 
    [ 5.000,  7.500) = 34218 
    [ 7.500, 10.000) = 3741 
    [10.000, 12.500) = 744 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     21.922 ms/op
     p(99.9900) =     31.916 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.788 ± 4.484  ops/ms
ClientPb.existUser                       thrpt       3   7.954 ± 6.752  ops/ms
ClientPb.getUser                         thrpt       3   7.910 ± 4.201  ops/ms
ClientPb.listUser                        thrpt       3   6.806 ± 0.950  ops/ms
ClientPb.createUser                       avgt       3   4.071 ± 2.193   ms/op
ClientPb.existUser                        avgt       3   3.839 ± 0.738   ms/op
ClientPb.getUser                          avgt       3   4.037 ± 0.834   ms/op
ClientPb.listUser                         avgt       3   4.775 ± 1.035   ms/op
ClientPb.createUser                     sample  237045   4.051 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.052           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.166           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.752           ms/op
ClientPb.existUser                      sample  243265   3.951 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.735           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.642           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.647           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.421           ms/op
ClientPb.getUser                        sample  234986   4.084 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.538           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.848           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.495           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.832           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.093           ms/op
ClientPb.listUser                       sample  200048   4.802 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.624           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.060           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.922           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.916           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.406           ms/op
