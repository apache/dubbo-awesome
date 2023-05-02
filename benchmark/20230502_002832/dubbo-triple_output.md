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
# Warmup Iteration   1: 0.978 ops/ms
# Warmup Iteration   2: 2.233 ops/ms
# Warmup Iteration   3: 4.242 ops/ms
Iteration   1: 5.227 ops/ms
Iteration   2: 5.351 ops/ms
Iteration   3: 5.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.400 ±(99.9%) 3.698 ops/ms [Average]
  (min, avg, max) = (5.227, 5.400, 5.623), stdev = 0.203
  CI (99.9%): [1.702, 9.099] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.397 ops/ms
# Warmup Iteration   2: 4.031 ops/ms
# Warmup Iteration   3: 5.448 ops/ms
Iteration   1: 5.765 ops/ms
Iteration   2: 5.884 ops/ms
Iteration   3: 5.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.835 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (5.765, 5.835, 5.884), stdev = 0.062
  CI (99.9%): [4.703, 6.968] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.420 ops/ms
# Warmup Iteration   2: 4.087 ops/ms
# Warmup Iteration   3: 5.310 ops/ms
Iteration   1: 5.264 ops/ms
Iteration   2: 5.384 ops/ms
Iteration   3: 5.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.398 ±(99.9%) 2.564 ops/ms [Average]
  (min, avg, max) = (5.264, 5.398, 5.544), stdev = 0.141
  CI (99.9%): [2.833, 7.962] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.423 ops/ms
# Warmup Iteration   2: 3.699 ops/ms
# Warmup Iteration   3: 4.651 ops/ms
Iteration   1: 4.716 ops/ms
Iteration   2: 4.833 ops/ms
Iteration   3: 4.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.726 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (4.630, 4.726, 4.833), stdev = 0.102
  CI (99.9%): [2.864, 6.588] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:56
# Fork: 1 of 1
# Warmup Iteration   1: 21.754 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 7.691 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.030 ±(99.9%) 0.013 ms/op
Iteration   1: 5.739 ±(99.9%) 0.023 ms/op
Iteration   2: 5.881 ±(99.9%) 0.017 ms/op
Iteration   3: 5.616 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.746 ±(99.9%) 2.421 ms/op [Average]
  (min, avg, max) = (5.616, 5.746, 5.881), stdev = 0.133
  CI (99.9%): [3.325, 8.166] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 17.190 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.478 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.748 ±(99.9%) 0.009 ms/op
Iteration   1: 5.668 ±(99.9%) 0.009 ms/op
Iteration   2: 5.623 ±(99.9%) 0.014 ms/op
Iteration   3: 5.532 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.608 ±(99.9%) 1.264 ms/op [Average]
  (min, avg, max) = (5.532, 5.608, 5.668), stdev = 0.069
  CI (99.9%): [4.343, 6.872] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 18.645 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.884 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.825 ±(99.9%) 0.011 ms/op
Iteration   1: 5.644 ±(99.9%) 0.010 ms/op
Iteration   2: 5.823 ±(99.9%) 0.011 ms/op
Iteration   3: 5.896 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.788 ±(99.9%) 2.361 ms/op [Average]
  (min, avg, max) = (5.644, 5.788, 5.896), stdev = 0.129
  CI (99.9%): [3.427, 8.148] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 19.366 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 8.297 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.921 ±(99.9%) 0.021 ms/op
Iteration   1: 6.705 ±(99.9%) 0.019 ms/op
Iteration   2: 6.811 ±(99.9%) 0.016 ms/op
Iteration   3: 6.711 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.742 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (6.705, 6.742, 6.811), stdev = 0.060
  CI (99.9%): [5.655, 7.830] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.185 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 8.319 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.314 ±(99.9%) 0.030 ms/op
Iteration   1: 5.734 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   5.415 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   7.782 ms/op
                 createUser·p0.99:   10.560 ms/op
                 createUser·p0.999:  30.065 ms/op
                 createUser·p0.9999: 41.978 ms/op
                 createUser·p1.00:   43.188 ms/op

Iteration   2: 5.685 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.662 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   6.881 ms/op
                 createUser·p0.95:   7.774 ms/op
                 createUser·p0.99:   10.895 ms/op
                 createUser·p0.999:  28.493 ms/op
                 createUser·p0.9999: 31.175 ms/op
                 createUser·p1.00:   32.342 ms/op

Iteration   3: 5.676 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.621 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.840 ms/op
                 createUser·p0.99:   11.469 ms/op
                 createUser·p0.999:  28.576 ms/op
                 createUser·p0.9999: 31.906 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168454
  mean =      5.698 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 42781 
    [ 5.000, 10.000) = 122996 
    [10.000, 15.000) = 2112 
    [15.000, 20.000) = 333 
    [20.000, 25.000) = 39 
    [25.000, 30.000) = 70 
    [30.000, 35.000) = 110 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.552 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     28.738 ms/op
     p(99.9900) =     33.781 ms/op
     p(99.9990) =     42.919 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.198 ±(99.9%) 0.386 ms/op
# Warmup Iteration   2: 7.001 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.529 ±(99.9%) 0.020 ms/op
Iteration   1: 5.663 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   5.300 ms/op
                 existUser·p0.90:   7.135 ms/op
                 existUser·p0.95:   8.520 ms/op
                 existUser·p0.99:   10.945 ms/op
                 existUser·p0.999:  16.351 ms/op
                 existUser·p0.9999: 29.186 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   2: 5.586 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   5.202 ms/op
                 existUser·p0.90:   7.070 ms/op
                 existUser·p0.95:   8.028 ms/op
                 existUser·p0.99:   10.568 ms/op
                 existUser·p0.999:  27.427 ms/op
                 existUser·p0.9999: 29.912 ms/op
                 existUser·p1.00:   30.933 ms/op

Iteration   3: 5.678 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   1.833 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   7.250 ms/op
                 existUser·p0.95:   8.585 ms/op
                 existUser·p0.99:   11.889 ms/op
                 existUser·p0.999:  28.223 ms/op
                 existUser·p0.9999: 45.613 ms/op
                 existUser·p1.00:   46.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170023
  mean =      5.642 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 60181 
    [ 5.000, 10.000) = 106684 
    [10.000, 15.000) = 2760 
    [15.000, 20.000) = 214 
    [20.000, 25.000) = 19 
    [25.000, 30.000) = 113 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.364 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     21.331 ms/op
     p(99.9900) =     43.778 ms/op
     p(99.9990) =     46.485 ms/op
     p(99.9999) =     46.531 ms/op
    p(100.0000) =     46.531 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.117 ±(99.9%) 0.329 ms/op
# Warmup Iteration   2: 7.758 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.049 ±(99.9%) 0.025 ms/op
Iteration   1: 5.901 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.250 ms/op
                 getUser·p0.95:   8.995 ms/op
                 getUser·p0.99:   12.878 ms/op
                 getUser·p0.999:  28.990 ms/op
                 getUser·p0.9999: 40.174 ms/op
                 getUser·p1.00:   40.829 ms/op

Iteration   2: 5.514 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   7.741 ms/op
                 getUser·p0.99:   10.565 ms/op
                 getUser·p0.999:  27.262 ms/op
                 getUser·p0.9999: 30.219 ms/op
                 getUser·p1.00:   31.130 ms/op

Iteration   3: 5.834 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.826 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.118 ms/op
                 getUser·p0.99:   11.174 ms/op
                 getUser·p0.999:  30.763 ms/op
                 getUser·p0.9999: 34.965 ms/op
                 getUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167123
  mean =      5.745 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 45289 
    [ 5.000, 10.000) = 118449 
    [10.000, 15.000) = 2907 
    [15.000, 20.000) = 207 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 110 
    [30.000, 35.000) = 88 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.217 ms/op
     p(99.0000) =     11.436 ms/op
     p(99.9000) =     28.471 ms/op
     p(99.9900) =     37.159 ms/op
     p(99.9990) =     40.697 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


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
# Warmup Iteration   1: 23.100 ±(99.9%) 0.419 ms/op
# Warmup Iteration   2: 8.472 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 7.091 ±(99.9%) 0.036 ms/op
Iteration   1: 6.870 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   6.455 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   13.091 ms/op
                 listUser·p0.999:  29.524 ms/op
                 listUser·p0.9999: 34.451 ms/op
                 listUser·p1.00:   35.586 ms/op

Iteration   2: 6.548 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  31.195 ms/op
                 listUser·p0.9999: 34.587 ms/op
                 listUser·p1.00:   35.979 ms/op

Iteration   3: 6.716 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.052 ms/op
                 listUser·p0.50:   6.365 ms/op
                 listUser·p0.90:   7.913 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   13.611 ms/op
                 listUser·p0.999:  30.380 ms/op
                 listUser·p0.9999: 34.437 ms/op
                 listUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143101
  mean =      6.709 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 2428 
    [ 5.000,  7.500) = 117869 
    [ 7.500, 10.000) = 17817 
    [10.000, 12.500) = 3281 
    [12.500, 15.000) = 1045 
    [15.000, 17.500) = 276 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 90 
    [32.500, 35.000) = 67 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      6.324 ms/op
     p(90.0000) =      8.102 ms/op
     p(95.0000) =      9.306 ms/op
     p(99.0000) =     13.222 ms/op
     p(99.9000) =     30.402 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     36.128 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.400 ± 3.698  ops/ms
ClientPb.existUser                       thrpt       3   5.835 ± 1.132  ops/ms
ClientPb.getUser                         thrpt       3   5.398 ± 2.564  ops/ms
ClientPb.listUser                        thrpt       3   4.726 ± 1.862  ops/ms
ClientPb.createUser                       avgt       3   5.746 ± 2.421   ms/op
ClientPb.existUser                        avgt       3   5.608 ± 1.264   ms/op
ClientPb.getUser                          avgt       3   5.788 ± 2.361   ms/op
ClientPb.listUser                         avgt       3   6.742 ± 1.087   ms/op
ClientPb.createUser                     sample  168454   5.698 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.552           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.799           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.010           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.738           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.781           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.188           ms/op
ClientPb.existUser                      sample  170023   5.642 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.043           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.364           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.125           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.331           ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.778           ms/op
ClientPb.existUser:existUser·p1.00      sample          46.531           ms/op
ClientPb.getUser                        sample  167123   5.745 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.871           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.374           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.217           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.436           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.471           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.159           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.829           ms/op
ClientPb.listUser                       sample  143101   6.709 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.974           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.324           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.102           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.222           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.406           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.241           ms/op
