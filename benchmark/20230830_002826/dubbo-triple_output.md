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
# Warmup Iteration   1: 1.085 ops/ms
# Warmup Iteration   2: 2.586 ops/ms
# Warmup Iteration   3: 5.120 ops/ms
Iteration   1: 5.646 ops/ms
Iteration   2: 5.833 ops/ms
Iteration   3: 5.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.701 ±(99.9%) 2.085 ops/ms [Average]
  (min, avg, max) = (5.625, 5.701, 5.833), stdev = 0.114
  CI (99.9%): [3.616, 7.787] (assumes normal distribution)


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
# Warmup Iteration   1: 1.770 ops/ms
# Warmup Iteration   2: 4.878 ops/ms
# Warmup Iteration   3: 6.054 ops/ms
Iteration   1: 6.161 ops/ms
Iteration   2: 6.287 ops/ms
Iteration   3: 6.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.225 ±(99.9%) 1.146 ops/ms [Average]
  (min, avg, max) = (6.161, 6.225, 6.287), stdev = 0.063
  CI (99.9%): [5.079, 7.370] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.648 ops/ms
# Warmup Iteration   2: 4.740 ops/ms
# Warmup Iteration   3: 5.870 ops/ms
Iteration   1: 6.012 ops/ms
Iteration   2: 5.871 ops/ms
Iteration   3: 6.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.975 ±(99.9%) 1.677 ops/ms [Average]
  (min, avg, max) = (5.871, 5.975, 6.043), stdev = 0.092
  CI (99.9%): [4.298, 7.652] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.475 ops/ms
# Warmup Iteration   2: 4.117 ops/ms
# Warmup Iteration   3: 4.676 ops/ms
Iteration   1: 5.145 ops/ms
Iteration   2: 5.291 ops/ms
Iteration   3: 5.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.301 ±(99.9%) 2.919 ops/ms [Average]
  (min, avg, max) = (5.145, 5.301, 5.465), stdev = 0.160
  CI (99.9%): [2.382, 8.219] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 15.987 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.840 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.248 ±(99.9%) 0.014 ms/op
Iteration   1: 5.087 ±(99.9%) 0.010 ms/op
Iteration   2: 5.406 ±(99.9%) 0.010 ms/op
Iteration   3: 5.294 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.262 ±(99.9%) 2.947 ms/op [Average]
  (min, avg, max) = (5.087, 5.262, 5.406), stdev = 0.162
  CI (99.9%): [2.315, 8.209] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 15.969 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.825 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.044 ±(99.9%) 0.008 ms/op
Iteration   1: 5.089 ±(99.9%) 0.008 ms/op
Iteration   2: 4.958 ±(99.9%) 0.009 ms/op
Iteration   3: 5.048 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.032 ±(99.9%) 1.225 ms/op [Average]
  (min, avg, max) = (4.958, 5.032, 5.089), stdev = 0.067
  CI (99.9%): [3.806, 6.257] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.026 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.913 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.298 ±(99.9%) 0.009 ms/op
Iteration   1: 5.263 ±(99.9%) 0.007 ms/op
Iteration   2: 5.274 ±(99.9%) 0.009 ms/op
Iteration   3: 5.197 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.245 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (5.197, 5.245, 5.274), stdev = 0.042
  CI (99.9%): [4.482, 6.007] (assumes normal distribution)


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
# Warmup Iteration   1: 19.706 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 8.504 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.614 ±(99.9%) 0.010 ms/op
Iteration   1: 6.456 ±(99.9%) 0.013 ms/op
Iteration   2: 6.358 ±(99.9%) 0.011 ms/op
Iteration   3: 6.208 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.341 ±(99.9%) 2.273 ms/op [Average]
  (min, avg, max) = (6.208, 6.341, 6.456), stdev = 0.125
  CI (99.9%): [4.068, 8.613] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 16.242 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 5.963 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.519 ±(99.9%) 0.025 ms/op
Iteration   1: 5.116 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.494 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.373 ms/op
                 createUser·p0.95:   7.430 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  21.575 ms/op
                 createUser·p0.9999: 25.461 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 5.308 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.081 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.356 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  26.044 ms/op
                 createUser·p0.9999: 32.014 ms/op
                 createUser·p1.00:   32.113 ms/op

Iteration   3: 5.123 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.519 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.177 ms/op
                 createUser·p0.95:   6.947 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  29.688 ms/op
                 createUser·p0.9999: 38.865 ms/op
                 createUser·p1.00:   39.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185206
  mean =      5.181 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 100459 
    [ 5.000,  7.500) = 76775 
    [ 7.500, 10.000) = 5788 
    [10.000, 12.500) = 1430 
    [12.500, 15.000) = 326 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.081 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.250 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     25.349 ms/op
     p(99.9900) =     36.173 ms/op
     p(99.9990) =     39.256 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


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
# Warmup Iteration   1: 14.292 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.273 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.171 ±(99.9%) 0.021 ms/op
Iteration   1: 4.849 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   4.489 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   7.553 ms/op
                 existUser·p0.99:   10.437 ms/op
                 existUser·p0.999:  22.782 ms/op
                 existUser·p0.9999: 32.828 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   2: 5.107 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.003 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.511 ms/op
                 existUser·p0.95:   7.332 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  25.571 ms/op
                 existUser·p0.9999: 29.072 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   3: 4.822 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.019 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   6.857 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  19.071 ms/op
                 existUser·p0.9999: 34.060 ms/op
                 existUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 195031
  mean =      4.923 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 132 
    [ 2.500,  5.000) = 131811 
    [ 5.000,  7.500) = 54978 
    [ 7.500, 10.000) = 6109 
    [10.000, 12.500) = 1213 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.250 ms/op
     p(95.0000) =      7.250 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     24.673 ms/op
     p(99.9900) =     32.915 ms/op
     p(99.9990) =     35.062 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 16.665 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 5.942 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.405 ±(99.9%) 0.020 ms/op
Iteration   1: 5.227 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.277 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.747 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   11.452 ms/op
                 getUser·p0.999:  19.425 ms/op
                 getUser·p0.9999: 23.818 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 5.123 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.686 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   6.324 ms/op
                 getUser·p0.95:   7.389 ms/op
                 getUser·p0.99:   10.830 ms/op
                 getUser·p0.999:  21.430 ms/op
                 getUser·p0.9999: 23.941 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 5.085 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.226 ms/op
                 getUser·p0.95:   7.160 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  20.288 ms/op
                 getUser·p0.9999: 24.228 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 186429
  mean =      5.144 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 106076 
    [ 5.000,  7.500) = 70368 
    [ 7.500, 10.000) = 7441 
    [10.000, 12.500) = 1585 
    [12.500, 15.000) = 412 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.610 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     20.597 ms/op
     p(99.9900) =     23.801 ms/op
     p(99.9990) =     25.712 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 18.803 ±(99.9%) 0.270 ms/op
# Warmup Iteration   2: 7.396 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.263 ±(99.9%) 0.026 ms/op
Iteration   1: 5.896 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  27.369 ms/op
                 listUser·p0.9999: 34.567 ms/op
                 listUser·p1.00:   35.324 ms/op

Iteration   2: 6.039 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  26.903 ms/op
                 listUser·p0.9999: 30.802 ms/op
                 listUser·p1.00:   32.440 ms/op

Iteration   3: 5.906 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.937 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.249 ms/op
                 listUser·p0.99:   12.222 ms/op
                 listUser·p0.999:  21.586 ms/op
                 listUser·p0.9999: 28.298 ms/op
                 listUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 161338
  mean =      5.947 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 26602 
    [ 5.000,  7.500) = 121919 
    [ 7.500, 10.000) = 8960 
    [10.000, 12.500) = 2567 
    [12.500, 15.000) = 725 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.127 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     25.919 ms/op
     p(99.9900) =     33.056 ms/op
     p(99.9990) =     35.324 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.701 ± 2.085  ops/ms
ClientPb.existUser                       thrpt       3   6.225 ± 1.146  ops/ms
ClientPb.getUser                         thrpt       3   5.975 ± 1.677  ops/ms
ClientPb.listUser                        thrpt       3   5.301 ± 2.919  ops/ms
ClientPb.createUser                       avgt       3   5.262 ± 2.947   ms/op
ClientPb.existUser                        avgt       3   5.032 ± 1.225   ms/op
ClientPb.getUser                          avgt       3   5.245 ± 0.763   ms/op
ClientPb.listUser                         avgt       3   6.341 ± 2.273   ms/op
ClientPb.createUser                     sample  185206   5.181 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.081           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.332           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.250           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.338           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.349           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.173           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.256           ms/op
ClientPb.existUser                      sample  195031   4.923 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.036           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.604           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.250           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.673           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.915           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.062           ms/op
ClientPb.getUser                        sample  186429   5.144 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.686           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.858           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.610           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.748           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.597           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.801           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.477           ms/op
ClientPb.listUser                       sample  161338   5.947 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.114           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.960           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.919           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.056           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.324           ms/op
