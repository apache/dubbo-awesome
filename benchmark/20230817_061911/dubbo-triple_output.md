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
# Warmup Iteration   1: 1.103 ops/ms
# Warmup Iteration   2: 2.377 ops/ms
# Warmup Iteration   3: 4.905 ops/ms
Iteration   1: 5.633 ops/ms
Iteration   2: 5.336 ops/ms
Iteration   3: 5.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.548 ±(99.9%) 3.373 ops/ms [Average]
  (min, avg, max) = (5.336, 5.548, 5.675), stdev = 0.185
  CI (99.9%): [2.175, 8.921] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.446 ops/ms
# Warmup Iteration   2: 4.197 ops/ms
# Warmup Iteration   3: 5.866 ops/ms
Iteration   1: 5.518 ops/ms
Iteration   2: 5.774 ops/ms
Iteration   3: 5.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.707 ±(99.9%) 3.033 ops/ms [Average]
  (min, avg, max) = (5.518, 5.707, 5.831), stdev = 0.166
  CI (99.9%): [2.674, 8.741] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.576 ops/ms
# Warmup Iteration   2: 4.707 ops/ms
# Warmup Iteration   3: 5.677 ops/ms
Iteration   1: 5.770 ops/ms
Iteration   2: 5.771 ops/ms
Iteration   3: 5.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.772 ±(99.9%) 0.048 ops/ms [Average]
  (min, avg, max) = (5.770, 5.772, 5.775), stdev = 0.003
  CI (99.9%): [5.724, 5.820] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.511 ops/ms
# Warmup Iteration   2: 3.954 ops/ms
# Warmup Iteration   3: 4.403 ops/ms
Iteration   1: 4.865 ops/ms
Iteration   2: 4.963 ops/ms
Iteration   3: 4.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.864 ±(99.9%) 1.796 ops/ms [Average]
  (min, avg, max) = (4.766, 4.864, 4.963), stdev = 0.098
  CI (99.9%): [3.069, 6.660] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 20.406 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.537 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.983 ±(99.9%) 0.013 ms/op
Iteration   1: 5.754 ±(99.9%) 0.011 ms/op
Iteration   2: 5.610 ±(99.9%) 0.014 ms/op
Iteration   3: 5.490 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.618 ±(99.9%) 2.416 ms/op [Average]
  (min, avg, max) = (5.490, 5.618, 5.754), stdev = 0.132
  CI (99.9%): [3.202, 8.035] (assumes normal distribution)


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
# Warmup Iteration   1: 16.295 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 7.086 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.600 ±(99.9%) 0.008 ms/op
Iteration   1: 5.509 ±(99.9%) 0.011 ms/op
Iteration   2: 5.324 ±(99.9%) 0.017 ms/op
Iteration   3: 5.360 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.398 ±(99.9%) 1.793 ms/op [Average]
  (min, avg, max) = (5.324, 5.398, 5.509), stdev = 0.098
  CI (99.9%): [3.605, 7.191] (assumes normal distribution)


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
# Warmup Iteration   1: 18.999 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.360 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.895 ±(99.9%) 0.009 ms/op
Iteration   1: 5.712 ±(99.9%) 0.008 ms/op
Iteration   2: 5.665 ±(99.9%) 0.010 ms/op
Iteration   3: 5.752 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.710 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (5.665, 5.710, 5.752), stdev = 0.044
  CI (99.9%): [4.909, 6.510] (assumes normal distribution)


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
# Warmup Iteration   1: 20.107 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.303 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.640 ±(99.9%) 0.010 ms/op
Iteration   1: 6.529 ±(99.9%) 0.011 ms/op
Iteration   2: 6.246 ±(99.9%) 0.018 ms/op
Iteration   3: 6.374 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.383 ±(99.9%) 2.584 ms/op [Average]
  (min, avg, max) = (6.246, 6.383, 6.529), stdev = 0.142
  CI (99.9%): [3.799, 8.966] (assumes normal distribution)


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
# Warmup Iteration   1: 21.849 ±(99.9%) 0.384 ms/op
# Warmup Iteration   2: 8.239 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.304 ±(99.9%) 0.030 ms/op
Iteration   1: 5.760 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.245 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   7.053 ms/op
                 createUser·p0.95:   8.348 ms/op
                 createUser·p0.99:   11.764 ms/op
                 createUser·p0.999:  25.785 ms/op
                 createUser·p0.9999: 31.661 ms/op
                 createUser·p1.00:   32.276 ms/op

Iteration   2: 5.571 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.652 ms/op
                 createUser·p0.95:   7.403 ms/op
                 createUser·p0.99:   10.732 ms/op
                 createUser·p0.999:  25.639 ms/op
                 createUser·p0.9999: 32.399 ms/op
                 createUser·p1.00:   33.161 ms/op

Iteration   3: 5.622 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.822 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   6.906 ms/op
                 createUser·p0.95:   8.053 ms/op
                 createUser·p0.99:   10.977 ms/op
                 createUser·p0.999:  27.989 ms/op
                 createUser·p0.9999: 30.976 ms/op
                 createUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169944
  mean =      5.650 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 43646 
    [ 5.000,  7.500) = 115463 
    [ 7.500, 10.000) = 7995 
    [10.000, 12.500) = 1788 
    [12.500, 15.000) = 623 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.946 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     26.020 ms/op
     p(99.9900) =     31.720 ms/op
     p(99.9990) =     32.817 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 18.182 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.627 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.777 ±(99.9%) 0.023 ms/op
Iteration   1: 5.313 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.169 ms/op
                 existUser·p0.95:   7.127 ms/op
                 existUser·p0.99:   10.486 ms/op
                 existUser·p0.999:  27.243 ms/op
                 existUser·p0.9999: 31.687 ms/op
                 existUser·p1.00:   35.193 ms/op

Iteration   2: 5.497 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.658 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   8.192 ms/op
                 existUser·p0.99:   12.161 ms/op
                 existUser·p0.999:  26.885 ms/op
                 existUser·p0.9999: 34.418 ms/op
                 existUser·p1.00:   34.669 ms/op

Iteration   3: 5.467 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.964 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   7.479 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  14.614 ms/op
                 existUser·p0.9999: 30.466 ms/op
                 existUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176887
  mean =      5.424 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 71279 
    [ 5.000,  7.500) = 96342 
    [ 7.500, 10.000) = 6600 
    [10.000, 12.500) = 1725 
    [12.500, 15.000) = 532 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.504 ms/op
     p(95.0000) =      7.594 ms/op
     p(99.0000) =     10.946 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     32.975 ms/op
     p(99.9990) =     34.790 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.717 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 7.342 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.722 ±(99.9%) 0.021 ms/op
Iteration   1: 5.872 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   5.497 ms/op
                 getUser·p0.90:   7.201 ms/op
                 getUser·p0.95:   8.507 ms/op
                 getUser·p0.99:   13.926 ms/op
                 getUser·p0.999:  18.762 ms/op
                 getUser·p0.9999: 28.178 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   2: 5.772 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   7.242 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   12.698 ms/op
                 getUser·p0.999:  26.792 ms/op
                 getUser·p0.9999: 30.731 ms/op
                 getUser·p1.00:   31.326 ms/op

Iteration   3: 5.355 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.732 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.234 ms/op
                 getUser·p0.95:   6.889 ms/op
                 getUser·p0.99:   9.765 ms/op
                 getUser·p0.999:  29.353 ms/op
                 getUser·p0.9999: 33.330 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169521
  mean =      5.657 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 50675 
    [ 5.000,  7.500) = 107771 
    [ 7.500, 10.000) = 7343 
    [10.000, 12.500) = 2058 
    [12.500, 15.000) = 1034 
    [15.000, 17.500) = 243 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      8.012 ms/op
     p(99.0000) =     12.452 ms/op
     p(99.9000) =     24.885 ms/op
     p(99.9900) =     32.837 ms/op
     p(99.9990) =     33.594 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 20.478 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 8.771 ±(99.9%) 0.074 ms/op
# Warmup Iteration   3: 6.773 ±(99.9%) 0.030 ms/op
Iteration   1: 6.953 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   6.406 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   10.699 ms/op
                 listUser·p0.99:   14.664 ms/op
                 listUser·p0.999:  29.262 ms/op
                 listUser·p0.9999: 32.388 ms/op
                 listUser·p1.00:   33.096 ms/op

Iteration   2: 6.626 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.092 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.550 ms/op
                 listUser·p0.999:  34.734 ms/op
                 listUser·p0.9999: 41.299 ms/op
                 listUser·p1.00:   41.681 ms/op

Iteration   3: 6.714 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.150 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  27.492 ms/op
                 listUser·p0.9999: 31.145 ms/op
                 listUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141893
  mean =      6.761 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3179 
    [ 5.000, 10.000) = 132830 
    [10.000, 15.000) = 5093 
    [15.000, 20.000) = 485 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 95 
    [30.000, 35.000) = 129 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.890 ms/op
     p(50.0000) =      6.349 ms/op
     p(90.0000) =      8.077 ms/op
     p(95.0000) =      9.585 ms/op
     p(99.0000) =     13.533 ms/op
     p(99.9000) =     30.900 ms/op
     p(99.9900) =     40.358 ms/op
     p(99.9990) =     41.653 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.548 ± 3.373  ops/ms
ClientPb.existUser                       thrpt       3   5.707 ± 3.033  ops/ms
ClientPb.getUser                         thrpt       3   5.772 ± 0.048  ops/ms
ClientPb.listUser                        thrpt       3   4.864 ± 1.796  ops/ms
ClientPb.createUser                       avgt       3   5.618 ± 2.416   ms/op
ClientPb.existUser                        avgt       3   5.398 ± 1.793   ms/op
ClientPb.getUser                          avgt       3   5.710 ± 0.801   ms/op
ClientPb.listUser                         avgt       3   6.383 ± 2.584   ms/op
ClientPb.createUser                     sample  169944   5.650 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.245           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.946           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.239           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.020           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.720           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.161           ms/op
ClientPb.existUser                      sample  176887   5.424 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.046           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.504           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.594           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.946           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.940           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.975           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  169521   5.657 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.317           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.906           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.012           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.452           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.885           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.837           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  141893   6.761 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.890           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.349           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.077           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.585           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.533           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.900           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.358           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.681           ms/op
