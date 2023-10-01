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
# Warmup Iteration   2: 3.288 ops/ms
# Warmup Iteration   3: 6.915 ops/ms
Iteration   1: 7.424 ops/ms
Iteration   2: 7.815 ops/ms
Iteration   3: 7.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.659 ±(99.9%) 3.779 ops/ms [Average]
  (min, avg, max) = (7.424, 7.659, 7.815), stdev = 0.207
  CI (99.9%): [3.880, 11.438] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.213 ops/ms
# Warmup Iteration   2: 6.036 ops/ms
# Warmup Iteration   3: 7.880 ops/ms
Iteration   1: 8.159 ops/ms
Iteration   2: 8.176 ops/ms
Iteration   3: 8.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.194 ±(99.9%) 0.832 ops/ms [Average]
  (min, avg, max) = (8.159, 8.194, 8.245), stdev = 0.046
  CI (99.9%): [7.362, 9.026] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.192 ops/ms
# Warmup Iteration   2: 6.333 ops/ms
# Warmup Iteration   3: 7.811 ops/ms
Iteration   1: 7.870 ops/ms
Iteration   2: 8.085 ops/ms
Iteration   3: 8.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.008 ±(99.9%) 2.185 ops/ms [Average]
  (min, avg, max) = (7.870, 8.008, 8.085), stdev = 0.120
  CI (99.9%): [5.823, 10.192] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.954 ops/ms
# Warmup Iteration   2: 5.365 ops/ms
# Warmup Iteration   3: 6.613 ops/ms
Iteration   1: 6.787 ops/ms
Iteration   2: 6.520 ops/ms
Iteration   3: 7.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.769 ±(99.9%) 4.383 ops/ms [Average]
  (min, avg, max) = (6.520, 6.769, 7.000), stdev = 0.240
  CI (99.9%): [2.386, 11.152] (assumes normal distribution)


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
# Warmup Iteration   1: 12.639 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.368 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.007 ms/op
Iteration   1: 3.963 ±(99.9%) 0.006 ms/op
Iteration   2: 3.898 ±(99.9%) 0.003 ms/op
Iteration   3: 3.973 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.945 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (3.898, 3.945, 3.973), stdev = 0.041
  CI (99.9%): [3.202, 4.687] (assumes normal distribution)


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
# Warmup Iteration   1: 12.678 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.003 ms/op
Iteration   1: 3.781 ±(99.9%) 0.006 ms/op
Iteration   2: 3.747 ±(99.9%) 0.006 ms/op
Iteration   3: 3.812 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.780 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.747, 3.780, 3.812), stdev = 0.033
  CI (99.9%): [3.185, 4.374] (assumes normal distribution)


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
# Warmup Iteration   1: 13.368 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.006 ms/op
Iteration   1: 4.098 ±(99.9%) 0.005 ms/op
Iteration   2: 3.944 ±(99.9%) 0.007 ms/op
Iteration   3: 3.951 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.997 ±(99.9%) 1.588 ms/op [Average]
  (min, avg, max) = (3.944, 3.997, 4.098), stdev = 0.087
  CI (99.9%): [2.409, 5.586] (assumes normal distribution)


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
# Warmup Iteration   1: 14.643 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.740 ±(99.9%) 0.008 ms/op
Iteration   1: 4.694 ±(99.9%) 0.010 ms/op
Iteration   2: 4.834 ±(99.9%) 0.005 ms/op
Iteration   3: 4.708 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.745 ±(99.9%) 1.413 ms/op [Average]
  (min, avg, max) = (4.694, 4.745, 4.834), stdev = 0.077
  CI (99.9%): [3.332, 6.159] (assumes normal distribution)


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
# Warmup Iteration   1: 12.044 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.910 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.369 ±(99.9%) 0.018 ms/op
Iteration   1: 4.168 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.833 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   8.159 ms/op
                 createUser·p0.999:  22.938 ms/op
                 createUser·p0.9999: 25.875 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 3.923 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.659 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  25.804 ms/op
                 createUser·p0.9999: 30.154 ms/op
                 createUser·p1.00:   31.261 ms/op

Iteration   3: 4.080 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 33.714 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236737
  mean =      4.054 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 292 
    [ 2.500,  5.000) = 223924 
    [ 5.000,  7.500) = 9668 
    [ 7.500, 10.000) = 2020 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.659 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     31.839 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 12.434 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.012 ms/op
Iteration   1: 3.938 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  21.234 ms/op
                 existUser·p0.9999: 24.993 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 3.914 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  16.613 ms/op
                 existUser·p0.9999: 27.978 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   3: 3.922 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.954 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.747 ms/op
                 existUser·p0.999:  12.577 ms/op
                 existUser·p0.9999: 26.411 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244559
  mean =      3.925 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 316 
    [ 2.500,  5.000) = 234482 
    [ 5.000,  7.500) = 7518 
    [ 7.500, 10.000) = 1443 
    [10.000, 12.500) = 387 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     27.641 ms/op
     p(99.9990) =     28.217 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 12.425 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.012 ms/op
Iteration   1: 4.343 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.122 ms/op
                 getUser·p0.50:   4.088 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   6.604 ms/op
                 getUser·p0.99:   9.224 ms/op
                 getUser·p0.999:  17.671 ms/op
                 getUser·p0.9999: 21.004 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   2: 4.042 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.645 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  15.426 ms/op
                 getUser·p0.9999: 27.504 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   3: 4.190 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   4.076 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  22.348 ms/op
                 getUser·p0.9999: 24.850 ms/op
                 getUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229100
  mean =      4.188 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 214650 
    [ 5.000,  7.500) = 10426 
    [ 7.500, 10.000) = 2888 
    [10.000, 12.500) = 624 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.645 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     18.425 ms/op
     p(99.9900) =     26.319 ms/op
     p(99.9990) =     28.399 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 16.767 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 6.828 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.048 ±(99.9%) 0.021 ms/op
Iteration   1: 4.786 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  23.101 ms/op
                 listUser·p0.9999: 24.848 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 4.970 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   8.945 ms/op
                 listUser·p0.999:  19.182 ms/op
                 listUser·p0.9999: 25.746 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   3: 4.971 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  17.455 ms/op
                 listUser·p0.9999: 27.145 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195366
  mean =      4.907 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 139518 
    [ 5.000,  7.500) = 51050 
    [ 7.500, 10.000) = 3641 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      2.009 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     20.632 ms/op
     p(99.9900) =     25.884 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.659 ± 3.779  ops/ms
ClientPb.existUser                       thrpt       3   8.194 ± 0.832  ops/ms
ClientPb.getUser                         thrpt       3   8.008 ± 2.185  ops/ms
ClientPb.listUser                        thrpt       3   6.769 ± 4.383  ops/ms
ClientPb.createUser                       avgt       3   3.945 ± 0.743   ms/op
ClientPb.existUser                        avgt       3   3.780 ± 0.594   ms/op
ClientPb.getUser                          avgt       3   3.997 ± 1.588   ms/op
ClientPb.listUser                         avgt       3   4.745 ± 1.413   ms/op
ClientPb.createUser                     sample  236737   4.054 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.659           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.766           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.970           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.839           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.341           ms/op
ClientPb.existUser                      sample  244559   3.925 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.417           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.613           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.641           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.246           ms/op
ClientPb.getUser                        sample  229100   4.188 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.645           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.425           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.319           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.967           ms/op
ClientPb.listUser                       sample  195366   4.907 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.009           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.988           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.632           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.884           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.180           ms/op
