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
# Warmup Iteration   1: 0.984 ops/ms
# Warmup Iteration   2: 2.167 ops/ms
# Warmup Iteration   3: 4.751 ops/ms
Iteration   1: 5.407 ops/ms
Iteration   2: 5.698 ops/ms
Iteration   3: 5.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.555 ±(99.9%) 2.654 ops/ms [Average]
  (min, avg, max) = (5.407, 5.555, 5.698), stdev = 0.145
  CI (99.9%): [2.900, 8.209] (assumes normal distribution)


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
# Warmup Iteration   1: 1.500 ops/ms
# Warmup Iteration   2: 4.182 ops/ms
# Warmup Iteration   3: 5.742 ops/ms
Iteration   1: 5.985 ops/ms
Iteration   2: 6.071 ops/ms
Iteration   3: 6.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.049 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (5.985, 6.049, 6.090), stdev = 0.056
  CI (99.9%): [5.028, 7.069] (assumes normal distribution)


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
# Warmup Iteration   1: 1.398 ops/ms
# Warmup Iteration   2: 4.151 ops/ms
# Warmup Iteration   3: 5.540 ops/ms
Iteration   1: 5.693 ops/ms
Iteration   2: 5.541 ops/ms
Iteration   3: 5.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.636 ±(99.9%) 1.519 ops/ms [Average]
  (min, avg, max) = (5.541, 5.636, 5.693), stdev = 0.083
  CI (99.9%): [4.117, 7.156] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.367 ops/ms
# Warmup Iteration   2: 3.905 ops/ms
# Warmup Iteration   3: 4.859 ops/ms
Iteration   1: 4.759 ops/ms
Iteration   2: 4.874 ops/ms
Iteration   3: 4.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.794 ±(99.9%) 1.266 ops/ms [Average]
  (min, avg, max) = (4.750, 4.794, 4.874), stdev = 0.069
  CI (99.9%): [3.528, 6.061] (assumes normal distribution)


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
# Warmup Iteration   1: 19.558 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 7.349 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.008 ±(99.9%) 0.018 ms/op
Iteration   1: 5.887 ±(99.9%) 0.011 ms/op
Iteration   2: 5.835 ±(99.9%) 0.011 ms/op
Iteration   3: 5.729 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.817 ±(99.9%) 1.474 ms/op [Average]
  (min, avg, max) = (5.729, 5.817, 5.887), stdev = 0.081
  CI (99.9%): [4.343, 7.291] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.003 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 6.340 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.524 ±(99.9%) 0.007 ms/op
Iteration   1: 5.527 ±(99.9%) 0.010 ms/op
Iteration   2: 5.265 ±(99.9%) 0.019 ms/op
Iteration   3: 5.220 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.337 ±(99.9%) 3.016 ms/op [Average]
  (min, avg, max) = (5.220, 5.337, 5.527), stdev = 0.165
  CI (99.9%): [2.321, 8.354] (assumes normal distribution)


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
# Warmup Iteration   1: 17.721 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.630 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.786 ±(99.9%) 0.008 ms/op
Iteration   1: 5.900 ±(99.9%) 0.009 ms/op
Iteration   2: 5.717 ±(99.9%) 0.012 ms/op
Iteration   3: 5.749 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.789 ±(99.9%) 1.786 ms/op [Average]
  (min, avg, max) = (5.717, 5.789, 5.900), stdev = 0.098
  CI (99.9%): [4.003, 7.575] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 19.876 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 8.830 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.827 ±(99.9%) 0.013 ms/op
Iteration   1: 6.669 ±(99.9%) 0.012 ms/op
Iteration   2: 6.650 ±(99.9%) 0.015 ms/op
Iteration   3: 6.721 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.680 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (6.650, 6.680, 6.721), stdev = 0.037
  CI (99.9%): [6.013, 7.347] (assumes normal distribution)


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
# Warmup Iteration   1: 18.524 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 7.289 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.242 ±(99.9%) 0.030 ms/op
Iteration   1: 5.604 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   6.808 ms/op
                 createUser·p0.95:   7.717 ms/op
                 createUser·p0.99:   10.519 ms/op
                 createUser·p0.999:  26.240 ms/op
                 createUser·p0.9999: 37.702 ms/op
                 createUser·p1.00:   38.273 ms/op

Iteration   2: 5.571 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.781 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.313 ms/op
                 createUser·p0.99:   10.912 ms/op
                 createUser·p0.999:  17.305 ms/op
                 createUser·p0.9999: 32.285 ms/op
                 createUser·p1.00:   33.096 ms/op

Iteration   3: 5.785 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.494 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   7.881 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  28.409 ms/op
                 createUser·p0.9999: 33.075 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169770
  mean =      5.652 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 45844 
    [ 5.000,  7.500) = 114598 
    [ 7.500, 10.000) = 6769 
    [10.000, 12.500) = 1730 
    [12.500, 15.000) = 481 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     36.833 ms/op
     p(99.9990) =     38.182 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.675 ±(99.9%) 0.333 ms/op
# Warmup Iteration   2: 6.650 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.598 ±(99.9%) 0.021 ms/op
Iteration   1: 5.440 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.734 ms/op
                 existUser·p0.95:   7.873 ms/op
                 existUser·p0.99:   10.764 ms/op
                 existUser·p0.999:  14.500 ms/op
                 existUser·p0.9999: 26.484 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 5.618 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   6.971 ms/op
                 existUser·p0.95:   8.281 ms/op
                 existUser·p0.99:   11.518 ms/op
                 existUser·p0.999:  25.955 ms/op
                 existUser·p0.9999: 29.731 ms/op
                 existUser·p1.00:   31.719 ms/op

Iteration   3: 5.607 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   7.897 ms/op
                 existUser·p0.99:   10.781 ms/op
                 existUser·p0.999:  29.456 ms/op
                 existUser·p0.9999: 34.819 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172705
  mean =      5.554 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 65793 
    [ 5.000,  7.500) = 95831 
    [ 7.500, 10.000) = 8171 
    [10.000, 12.500) = 1946 
    [12.500, 15.000) = 471 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      8.028 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     22.681 ms/op
     p(99.9900) =     33.799 ms/op
     p(99.9990) =     36.426 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 18.695 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 7.502 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 5.987 ±(99.9%) 0.023 ms/op
Iteration   1: 5.615 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.150 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   6.799 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   11.076 ms/op
                 getUser·p0.999:  19.431 ms/op
                 getUser·p0.9999: 30.179 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   2: 5.843 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   7.332 ms/op
                 getUser·p0.95:   8.946 ms/op
                 getUser·p0.99:   12.780 ms/op
                 getUser·p0.999:  32.342 ms/op
                 getUser·p0.9999: 39.715 ms/op
                 getUser·p1.00:   41.157 ms/op

Iteration   3: 5.719 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.478 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   7.799 ms/op
                 getUser·p0.99:   11.849 ms/op
                 getUser·p0.999:  30.147 ms/op
                 getUser·p0.9999: 33.554 ms/op
                 getUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167785
  mean =      5.724 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 47780 
    [ 5.000, 10.000) = 115970 
    [10.000, 15.000) = 3468 
    [15.000, 20.000) = 347 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 92 
    [35.000, 40.000) = 34 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     24.452 ms/op
     p(99.9900) =     38.994 ms/op
     p(99.9990) =     40.357 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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
# Warmup Iteration   1: 22.136 ±(99.9%) 0.396 ms/op
# Warmup Iteration   2: 7.894 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.842 ±(99.9%) 0.029 ms/op
Iteration   1: 6.663 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   8.282 ms/op
                 listUser·p0.95:   10.142 ms/op
                 listUser·p0.99:   14.057 ms/op
                 listUser·p0.999:  28.837 ms/op
                 listUser·p0.9999: 31.595 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   2: 6.715 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   13.173 ms/op
                 listUser·p0.999:  30.696 ms/op
                 listUser·p0.9999: 35.208 ms/op
                 listUser·p1.00:   36.569 ms/op

Iteration   3: 6.607 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   7.758 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   13.091 ms/op
                 listUser·p0.999:  30.072 ms/op
                 listUser·p0.9999: 33.823 ms/op
                 listUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144024
  mean =      6.661 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 2732 
    [ 5.000,  7.500) = 119869 
    [ 7.500, 10.000) = 16017 
    [10.000, 12.500) = 3342 
    [12.500, 15.000) = 1192 
    [15.000, 17.500) = 479 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 127 
    [30.000, 32.500) = 95 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      6.250 ms/op
     p(90.0000) =      7.987 ms/op
     p(95.0000) =      9.306 ms/op
     p(99.0000) =     13.517 ms/op
     p(99.9000) =     29.751 ms/op
     p(99.9900) =     34.183 ms/op
     p(99.9990) =     36.540 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.555 ± 2.654  ops/ms
ClientPb.existUser                       thrpt       3   6.049 ± 1.021  ops/ms
ClientPb.getUser                         thrpt       3   5.636 ± 1.519  ops/ms
ClientPb.listUser                        thrpt       3   4.794 ± 1.266  ops/ms
ClientPb.createUser                       avgt       3   5.817 ± 1.474   ms/op
ClientPb.existUser                        avgt       3   5.337 ± 3.016   ms/op
ClientPb.getUser                          avgt       3   5.789 ± 1.786   ms/op
ClientPb.listUser                         avgt       3   6.680 ± 0.667   ms/op
ClientPb.createUser                     sample  169770   5.652 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.822           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.832           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.643           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.895           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.907           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.833           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.273           ms/op
ClientPb.existUser                      sample  172705   5.554 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.482           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.028           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.010           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.681           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.799           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  167785   5.724 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.500           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.341           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.438           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.878           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.452           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.994           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.157           ms/op
ClientPb.listUser                       sample  144024   6.661 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.097           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.250           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.987           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.517           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.751           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.183           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.569           ms/op
