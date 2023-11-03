# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.247 ops/ms
# Warmup Iteration   2: 2.622 ops/ms
# Warmup Iteration   3: 5.534 ops/ms
Iteration   1: 5.587 ops/ms
Iteration   2: 5.752 ops/ms
Iteration   3: 6.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.804 ±(99.9%) 4.530 ops/ms [Average]
  (min, avg, max) = (5.587, 5.804, 6.075), stdev = 0.248
  CI (99.9%): [1.275, 10.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.732 ops/ms
# Warmup Iteration   2: 5.254 ops/ms
# Warmup Iteration   3: 6.036 ops/ms
Iteration   1: 6.342 ops/ms
Iteration   2: 6.209 ops/ms
Iteration   3: 6.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.274 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (6.209, 6.274, 6.342), stdev = 0.066
  CI (99.9%): [5.062, 7.485] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.675 ops/ms
# Warmup Iteration   2: 4.508 ops/ms
# Warmup Iteration   3: 6.131 ops/ms
Iteration   1: 5.909 ops/ms
Iteration   2: 5.848 ops/ms
Iteration   3: 6.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.920 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (5.848, 5.920, 6.002), stdev = 0.078
  CI (99.9%): [4.501, 7.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.669 ops/ms
# Warmup Iteration   2: 3.856 ops/ms
# Warmup Iteration   3: 4.669 ops/ms
Iteration   1: 4.864 ops/ms
Iteration   2: 5.147 ops/ms
Iteration   3: 5.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.079 ±(99.9%) 3.459 ops/ms [Average]
  (min, avg, max) = (4.864, 5.079, 5.225), stdev = 0.190
  CI (99.9%): [1.620, 8.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.053 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.304 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.574 ±(99.9%) 0.009 ms/op
Iteration   1: 5.538 ±(99.9%) 0.009 ms/op
Iteration   2: 5.196 ±(99.9%) 0.012 ms/op
Iteration   3: 5.642 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.459 ±(99.9%) 4.253 ms/op [Average]
  (min, avg, max) = (5.196, 5.459, 5.642), stdev = 0.233
  CI (99.9%): [1.206, 9.712] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.076 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.795 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.353 ±(99.9%) 0.004 ms/op
Iteration   1: 5.170 ±(99.9%) 0.009 ms/op
Iteration   2: 5.175 ±(99.9%) 0.007 ms/op
Iteration   3: 5.065 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.137 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (5.065, 5.137, 5.175), stdev = 0.062
  CI (99.9%): [4.000, 6.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.031 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.113 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.487 ±(99.9%) 0.009 ms/op
Iteration   1: 5.211 ±(99.9%) 0.014 ms/op
Iteration   2: 5.389 ±(99.9%) 0.008 ms/op
Iteration   3: 5.350 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.317 ±(99.9%) 1.701 ms/op [Average]
  (min, avg, max) = (5.211, 5.317, 5.389), stdev = 0.093
  CI (99.9%): [3.615, 7.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.904 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 7.421 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.457 ±(99.9%) 0.012 ms/op
Iteration   1: 6.168 ±(99.9%) 0.019 ms/op
Iteration   2: 6.087 ±(99.9%) 0.019 ms/op
Iteration   3: 5.881 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.045 ±(99.9%) 2.702 ms/op [Average]
  (min, avg, max) = (5.881, 6.045, 6.168), stdev = 0.148
  CI (99.9%): [3.343, 8.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.878 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 6.629 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.700 ±(99.9%) 0.024 ms/op
Iteration   1: 5.485 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.906 ms/op
                 createUser·p0.95:   8.151 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 5.381 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.348 ms/op
                 createUser·p0.99:   9.650 ms/op
                 createUser·p0.999:  25.855 ms/op
                 createUser·p0.9999: 29.591 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 5.349 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.269 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.365 ms/op
                 createUser·p0.99:   10.076 ms/op
                 createUser·p0.999:  15.760 ms/op
                 createUser·p0.9999: 32.572 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177600
  mean =      5.404 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 78921 
    [ 5.000,  7.500) = 89096 
    [ 7.500, 10.000) = 7210 
    [10.000, 12.500) = 1597 
    [12.500, 15.000) = 453 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     33.351 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.799 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.923 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.264 ±(99.9%) 0.021 ms/op
Iteration   1: 5.416 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   7.225 ms/op
                 existUser·p0.95:   8.005 ms/op
                 existUser·p0.99:   9.945 ms/op
                 existUser·p0.999:  22.282 ms/op
                 existUser·p0.9999: 29.313 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   2: 5.093 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.105 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   6.414 ms/op
                 existUser·p0.95:   7.315 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  27.105 ms/op
                 existUser·p0.9999: 31.822 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 5.406 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   8.184 ms/op
                 existUser·p0.99:   11.404 ms/op
                 existUser·p0.999:  27.167 ms/op
                 existUser·p0.9999: 31.332 ms/op
                 existUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181063
  mean =      5.300 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 98715 
    [ 5.000,  7.500) = 70902 
    [ 7.500, 10.000) = 9180 
    [10.000, 12.500) = 1337 
    [12.500, 15.000) = 463 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     23.050 ms/op
     p(99.9900) =     31.483 ms/op
     p(99.9990) =     33.763 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.076 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.179 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.670 ±(99.9%) 0.021 ms/op
Iteration   1: 5.564 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.605 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.692 ms/op
                 getUser·p0.99:   11.583 ms/op
                 getUser·p0.999:  24.198 ms/op
                 getUser·p0.9999: 33.440 ms/op
                 getUser·p1.00:   35.258 ms/op

Iteration   2: 5.600 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.408 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   6.816 ms/op
                 getUser·p0.95:   7.897 ms/op
                 getUser·p0.99:   10.804 ms/op
                 getUser·p0.999:  26.930 ms/op
                 getUser·p0.9999: 30.722 ms/op
                 getUser·p1.00:   32.047 ms/op

Iteration   3: 5.443 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.888 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.509 ms/op
                 getUser·p0.95:   7.365 ms/op
                 getUser·p0.99:   10.207 ms/op
                 getUser·p0.999:  25.226 ms/op
                 getUser·p0.9999: 30.544 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173483
  mean =      5.535 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 61755 
    [ 5.000,  7.500) = 102327 
    [ 7.500, 10.000) = 6904 
    [10.000, 12.500) = 1463 
    [12.500, 15.000) = 490 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.408 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     25.052 ms/op
     p(99.9900) =     32.494 ms/op
     p(99.9990) =     34.969 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.425 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 8.389 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.480 ±(99.9%) 0.025 ms/op
Iteration   1: 6.289 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.162 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  24.761 ms/op
                 listUser·p0.9999: 27.391 ms/op
                 listUser·p1.00:   29.950 ms/op

Iteration   2: 6.475 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.937 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   12.403 ms/op
                 listUser·p0.999:  24.113 ms/op
                 listUser·p0.9999: 29.590 ms/op
                 listUser·p1.00:   32.997 ms/op

Iteration   3: 6.156 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  23.824 ms/op
                 listUser·p0.9999: 29.085 ms/op
                 listUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152160
  mean =      6.304 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 8109 
    [ 5.000,  7.500) = 127599 
    [ 7.500, 10.000) = 12925 
    [10.000, 12.500) = 2433 
    [12.500, 15.000) = 513 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      5.988 ms/op
     p(90.0000) =      7.602 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     24.510 ms/op
     p(99.9900) =     29.353 ms/op
     p(99.9990) =     31.476 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.804 ± 4.530  ops/ms
ClientPb.existUser                       thrpt       3   6.274 ± 1.212  ops/ms
ClientPb.getUser                         thrpt       3   5.920 ± 1.419  ops/ms
ClientPb.listUser                        thrpt       3   5.079 ± 3.459  ops/ms
ClientPb.createUser                       avgt       3   5.459 ± 4.253   ms/op
ClientPb.existUser                        avgt       3   5.137 ± 1.137   ms/op
ClientPb.getUser                          avgt       3   5.317 ± 1.701   ms/op
ClientPb.listUser                         avgt       3   6.045 ± 2.702   ms/op
ClientPb.createUser                     sample  177600   5.404 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.232           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.643           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.502           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.842           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  181063   5.300 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.616           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.906           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.864           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.486           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.050           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.483           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  173483   5.535 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.408           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.251           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.660           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.643           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.052           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.494           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.258           ms/op
ClientPb.listUser                       sample  152160   6.304 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.318           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.988           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.684           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.510           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.353           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.997           ms/op
