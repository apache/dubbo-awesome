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
# Warmup Iteration   1: 1.501 ops/ms
# Warmup Iteration   2: 3.469 ops/ms
# Warmup Iteration   3: 7.219 ops/ms
Iteration   1: 7.350 ops/ms
Iteration   2: 7.750 ops/ms
Iteration   3: 7.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.600 ±(99.9%) 3.988 ops/ms [Average]
  (min, avg, max) = (7.350, 7.600, 7.750), stdev = 0.219
  CI (99.9%): [3.613, 11.588] (assumes normal distribution)


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
# Warmup Iteration   1: 2.119 ops/ms
# Warmup Iteration   2: 6.268 ops/ms
# Warmup Iteration   3: 7.692 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 7.898 ops/ms
Iteration   3: 8.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.041 ±(99.9%) 5.841 ops/ms [Average]
  (min, avg, max) = (7.818, 8.041, 8.408), stdev = 0.320
  CI (99.9%): [2.200, 13.882] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.408 ops/ms
# Warmup Iteration   2: 6.672 ops/ms
# Warmup Iteration   3: 7.902 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 7.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.838 ±(99.9%) 2.089 ops/ms [Average]
  (min, avg, max) = (7.761, 7.838, 7.970), stdev = 0.115
  CI (99.9%): [5.749, 9.927] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.898 ops/ms
# Warmup Iteration   2: 5.629 ops/ms
# Warmup Iteration   3: 6.551 ops/ms
Iteration   1: 6.330 ops/ms
Iteration   2: 6.557 ops/ms
Iteration   3: 6.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.618 ±(99.9%) 5.893 ops/ms [Average]
  (min, avg, max) = (6.330, 6.618, 6.967), stdev = 0.323
  CI (99.9%): [0.725, 12.511] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.793 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.028 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.415 ±(99.9%) 0.007 ms/op
Iteration   1: 4.218 ±(99.9%) 0.006 ms/op
Iteration   2: 4.107 ±(99.9%) 0.006 ms/op
Iteration   3: 4.092 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.139 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (4.092, 4.139, 4.218), stdev = 0.069
  CI (99.9%): [2.876, 5.402] (assumes normal distribution)


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
# Warmup Iteration   1: 11.025 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.332 ±(99.9%) 0.004 ms/op
Iteration   1: 4.167 ±(99.9%) 0.004 ms/op
Iteration   2: 4.011 ±(99.9%) 0.006 ms/op
Iteration   3: 3.964 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.048 ±(99.9%) 1.938 ms/op [Average]
  (min, avg, max) = (3.964, 4.048, 4.167), stdev = 0.106
  CI (99.9%): [2.109, 5.986] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.232 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.666 ±(99.9%) 0.005 ms/op
Iteration   1: 4.346 ±(99.9%) 0.004 ms/op
Iteration   2: 4.086 ±(99.9%) 0.007 ms/op
Iteration   3: 4.173 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.202 ±(99.9%) 2.409 ms/op [Average]
  (min, avg, max) = (4.086, 4.202, 4.346), stdev = 0.132
  CI (99.9%): [1.792, 6.611] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.321 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.917 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.310 ±(99.9%) 0.009 ms/op
Iteration   1: 5.033 ±(99.9%) 0.006 ms/op
Iteration   2: 4.973 ±(99.9%) 0.008 ms/op
Iteration   3: 5.076 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.027 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (4.973, 5.027, 5.076), stdev = 0.052
  CI (99.9%): [4.083, 5.972] (assumes normal distribution)


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
# Warmup Iteration   1: 14.623 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 5.536 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.669 ±(99.9%) 0.021 ms/op
Iteration   1: 4.096 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.923 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  26.043 ms/op
                 createUser·p0.9999: 28.784 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   2: 4.157 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   8.404 ms/op
                 createUser·p0.999:  15.189 ms/op
                 createUser·p0.9999: 30.058 ms/op
                 createUser·p1.00:   30.310 ms/op

Iteration   3: 4.115 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  29.853 ms/op
                 createUser·p0.9999: 37.028 ms/op
                 createUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232930
  mean =      4.123 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190 
    [ 2.500,  5.000) = 215449 
    [ 5.000,  7.500) = 13742 
    [ 7.500, 10.000) = 2016 
    [10.000, 12.500) = 825 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 112 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     26.806 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.045 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.765 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.015 ms/op
Iteration   1: 3.896 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.803 ms/op
                 existUser·p0.999:  12.468 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   31.818 ms/op

Iteration   2: 3.875 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.006 ms/op
                 existUser·p0.999:  25.002 ms/op
                 existUser·p0.9999: 28.836 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   3: 4.010 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   8.166 ms/op
                 existUser·p0.999:  14.783 ms/op
                 existUser·p0.9999: 31.557 ms/op
                 existUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244335
  mean =      3.926 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 367 
    [ 2.500,  5.000) = 230943 
    [ 5.000,  7.500) = 10203 
    [ 7.500, 10.000) = 2036 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 12.586 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 5.354 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.380 ±(99.9%) 0.018 ms/op
Iteration   1: 4.160 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  25.526 ms/op
                 getUser·p0.9999: 34.171 ms/op
                 getUser·p1.00:   35.324 ms/op

Iteration   2: 4.257 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.927 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   5.864 ms/op
                 getUser·p0.99:   8.257 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 28.819 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 4.362 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.839 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   6.685 ms/op
                 getUser·p0.99:   9.617 ms/op
                 getUser·p0.999:  18.419 ms/op
                 getUser·p0.9999: 36.504 ms/op
                 getUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 225410
  mean =      4.258 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 201642 
    [ 5.000,  7.500) = 18781 
    [ 7.500, 10.000) = 3350 
    [10.000, 12.500) = 978 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     19.457 ms/op
     p(99.9900) =     34.633 ms/op
     p(99.9990) =     36.880 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 14.792 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 6.192 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.338 ±(99.9%) 0.025 ms/op
Iteration   1: 5.022 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   7.569 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  27.471 ms/op
                 listUser·p0.9999: 31.234 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   2: 5.067 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.736 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   10.519 ms/op
                 listUser·p0.999:  19.323 ms/op
                 listUser·p0.9999: 29.186 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   3: 4.840 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.691 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.339 ms/op
                 listUser·p0.99:   9.623 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 23.078 ms/op
                 listUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192861
  mean =      4.974 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 136126 
    [ 5.000,  7.500) = 48723 
    [ 7.500, 10.000) = 6094 
    [10.000, 12.500) = 1255 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.030 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     29.744 ms/op
     p(99.9990) =     31.958 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.600 ± 3.988  ops/ms
ClientPb.existUser                       thrpt       3   8.041 ± 5.841  ops/ms
ClientPb.getUser                         thrpt       3   7.838 ± 2.089  ops/ms
ClientPb.listUser                        thrpt       3   6.618 ± 5.893  ops/ms
ClientPb.createUser                       avgt       3   4.139 ± 1.263   ms/op
ClientPb.existUser                        avgt       3   4.048 ± 1.938   ms/op
ClientPb.getUser                          avgt       3   4.202 ± 2.409   ms/op
ClientPb.listUser                         avgt       3   5.027 ± 0.945   ms/op
ClientPb.createUser                     sample  232930   4.123 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.653           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.733           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.806           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.372           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.683           ms/op
ClientPb.existUser                      sample  244335   3.926 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.530           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.054           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.684           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.582           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.802           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.670           ms/op
ClientPb.getUser                        sample  225410   4.258 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.515           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.054           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.995           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.457           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.633           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.093           ms/op
ClientPb.listUser                       sample  192861   4.974 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.030           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.994           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.955           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.744           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.080           ms/op
