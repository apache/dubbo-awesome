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
# Warmup Iteration   1: 1.229 ops/ms
# Warmup Iteration   2: 2.998 ops/ms
# Warmup Iteration   3: 6.075 ops/ms
Iteration   1: 5.788 ops/ms
Iteration   2: 6.200 ops/ms
Iteration   3: 6.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.079 ±(99.9%) 4.629 ops/ms [Average]
  (min, avg, max) = (5.788, 6.079, 6.250), stdev = 0.254
  CI (99.9%): [1.450, 10.709] (assumes normal distribution)


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
# Warmup Iteration   1: 1.719 ops/ms
# Warmup Iteration   2: 5.092 ops/ms
# Warmup Iteration   3: 5.864 ops/ms
Iteration   1: 6.184 ops/ms
Iteration   2: 6.424 ops/ms
Iteration   3: 6.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.313 ±(99.9%) 2.203 ops/ms [Average]
  (min, avg, max) = (6.184, 6.313, 6.424), stdev = 0.121
  CI (99.9%): [4.110, 8.516] (assumes normal distribution)


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
# Warmup Iteration   1: 1.839 ops/ms
# Warmup Iteration   2: 5.472 ops/ms
# Warmup Iteration   3: 5.993 ops/ms
Iteration   1: 6.078 ops/ms
Iteration   2: 6.480 ops/ms
Iteration   3: 6.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.212 ±(99.9%) 4.238 ops/ms [Average]
  (min, avg, max) = (6.077, 6.212, 6.480), stdev = 0.232
  CI (99.9%): [1.973, 10.450] (assumes normal distribution)


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
# Warmup Iteration   1: 1.681 ops/ms
# Warmup Iteration   2: 4.193 ops/ms
# Warmup Iteration   3: 5.149 ops/ms
Iteration   1: 5.363 ops/ms
Iteration   2: 5.371 ops/ms
Iteration   3: 5.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.271 ±(99.9%) 3.031 ops/ms [Average]
  (min, avg, max) = (5.079, 5.271, 5.371), stdev = 0.166
  CI (99.9%): [2.240, 8.302] (assumes normal distribution)


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
# Warmup Iteration   1: 16.771 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.004 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.720 ±(99.9%) 0.013 ms/op
Iteration   1: 5.202 ±(99.9%) 0.011 ms/op
Iteration   2: 5.356 ±(99.9%) 0.006 ms/op
Iteration   3: 5.323 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.294 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (5.202, 5.294, 5.356), stdev = 0.081
  CI (99.9%): [3.816, 6.771] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.214 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.172 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.240 ±(99.9%) 0.013 ms/op
Iteration   1: 5.137 ±(99.9%) 0.013 ms/op
Iteration   2: 5.134 ±(99.9%) 0.012 ms/op
Iteration   3: 5.013 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.095 ±(99.9%) 1.295 ms/op [Average]
  (min, avg, max) = (5.013, 5.095, 5.137), stdev = 0.071
  CI (99.9%): [3.800, 6.390] (assumes normal distribution)


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
# Warmup Iteration   1: 16.102 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.848 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.318 ±(99.9%) 0.003 ms/op
Iteration   1: 5.219 ±(99.9%) 0.009 ms/op
Iteration   2: 5.439 ±(99.9%) 0.010 ms/op
Iteration   3: 5.689 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.449 ±(99.9%) 4.283 ms/op [Average]
  (min, avg, max) = (5.219, 5.449, 5.689), stdev = 0.235
  CI (99.9%): [1.167, 9.732] (assumes normal distribution)


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
# Warmup Iteration   1: 17.266 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.952 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.441 ±(99.9%) 0.009 ms/op
Iteration   1: 6.321 ±(99.9%) 0.009 ms/op
Iteration   2: 6.192 ±(99.9%) 0.009 ms/op
Iteration   3: 6.051 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.188 ±(99.9%) 2.463 ms/op [Average]
  (min, avg, max) = (6.051, 6.188, 6.321), stdev = 0.135
  CI (99.9%): [3.725, 8.651] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.336 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 6.298 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.751 ±(99.9%) 0.026 ms/op
Iteration   1: 5.741 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.021 ms/op
                 createUser·p0.50:   5.521 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.118 ms/op
                 createUser·p0.99:   11.010 ms/op
                 createUser·p0.999:  26.206 ms/op
                 createUser·p0.9999: 31.261 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 5.277 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.948 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.980 ms/op
                 createUser·p0.95:   7.913 ms/op
                 createUser·p0.99:   10.469 ms/op
                 createUser·p0.999:  21.430 ms/op
                 createUser·p0.9999: 26.767 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   3: 5.221 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.015 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.767 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  35.177 ms/op
                 createUser·p0.9999: 39.059 ms/op
                 createUser·p1.00:   39.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177615
  mean =      5.403 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 80337 
    [ 5.000,  7.500) = 84675 
    [ 7.500, 10.000) = 10154 
    [10.000, 12.500) = 1617 
    [12.500, 15.000) = 368 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.948 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      7.078 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     25.257 ms/op
     p(99.9900) =     37.633 ms/op
     p(99.9990) =     39.497 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.064 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 6.044 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.190 ±(99.9%) 0.020 ms/op
Iteration   1: 4.907 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.997 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   6.906 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  13.640 ms/op
                 existUser·p0.9999: 25.475 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   2: 5.470 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.054 ms/op
                 existUser·p0.50:   5.202 ms/op
                 existUser·p0.90:   7.037 ms/op
                 existUser·p0.95:   8.192 ms/op
                 existUser·p0.99:   10.502 ms/op
                 existUser·p0.999:  22.385 ms/op
                 existUser·p0.9999: 26.870 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   3: 5.234 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.812 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.595 ms/op
                 existUser·p0.95:   7.283 ms/op
                 existUser·p0.99:   9.994 ms/op
                 existUser·p0.999:  23.097 ms/op
                 existUser·p0.9999: 30.641 ms/op
                 existUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184815
  mean =      5.193 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 96430 
    [ 5.000,  7.500) = 79500 
    [ 7.500, 10.000) = 6832 
    [10.000, 12.500) = 1513 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.438 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     20.715 ms/op
     p(99.9900) =     29.049 ms/op
     p(99.9990) =     34.335 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 16.192 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 6.454 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.374 ±(99.9%) 0.021 ms/op
Iteration   1: 5.624 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   7.242 ms/op
                 getUser·p0.95:   8.323 ms/op
                 getUser·p0.99:   12.403 ms/op
                 getUser·p0.999:  22.748 ms/op
                 getUser·p0.9999: 25.739 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 5.426 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.355 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   6.930 ms/op
                 getUser·p0.95:   7.774 ms/op
                 getUser·p0.99:   10.191 ms/op
                 getUser·p0.999:  23.032 ms/op
                 getUser·p0.9999: 29.032 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   3: 5.425 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.980 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.767 ms/op
                 getUser·p0.95:   7.610 ms/op
                 getUser·p0.99:   10.846 ms/op
                 getUser·p0.999:  27.197 ms/op
                 getUser·p0.9999: 31.598 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174923
  mean =      5.490 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 69342 
    [ 5.000,  7.500) = 93698 
    [ 7.500, 10.000) = 9142 
    [10.000, 12.500) = 1673 
    [12.500, 15.000) = 625 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.980 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     11.108 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     30.835 ms/op
     p(99.9990) =     32.309 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 16.563 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 6.934 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.244 ±(99.9%) 0.027 ms/op
Iteration   1: 6.212 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   7.864 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   12.354 ms/op
                 listUser·p0.999:  26.149 ms/op
                 listUser·p0.9999: 29.547 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   2: 6.327 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.646 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   12.517 ms/op
                 listUser·p0.999:  26.575 ms/op
                 listUser·p0.9999: 34.920 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 6.269 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   8.266 ms/op
                 listUser·p0.95:   9.617 ms/op
                 listUser·p0.99:   14.418 ms/op
                 listUser·p0.999:  21.726 ms/op
                 listUser·p0.9999: 24.576 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153005
  mean =      6.269 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 24412 
    [ 5.000,  7.500) = 107381 
    [ 7.500, 10.000) = 15945 
    [10.000, 12.500) = 3311 
    [12.500, 15.000) = 1114 
    [15.000, 17.500) = 436 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.999 ms/op
     p(50.0000) =      5.882 ms/op
     p(90.0000) =      8.020 ms/op
     p(95.0000) =      9.241 ms/op
     p(99.0000) =     13.140 ms/op
     p(99.9000) =     25.330 ms/op
     p(99.9900) =     33.063 ms/op
     p(99.9990) =     35.682 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.079 ± 4.629  ops/ms
ClientPb.existUser                       thrpt       3   6.313 ± 2.203  ops/ms
ClientPb.getUser                         thrpt       3   6.212 ± 4.238  ops/ms
ClientPb.listUser                        thrpt       3   5.271 ± 3.031  ops/ms
ClientPb.createUser                       avgt       3   5.294 ± 1.478   ms/op
ClientPb.existUser                        avgt       3   5.095 ± 1.295   ms/op
ClientPb.getUser                          avgt       3   5.449 ± 4.283   ms/op
ClientPb.listUser                         avgt       3   6.188 ± 2.463   ms/op
ClientPb.createUser                     sample  177615   5.403 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.948           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.078           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.922           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.535           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.257           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.633           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.649           ms/op
ClientPb.existUser                      sample  184815   5.193 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.812           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.627           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.438           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.093           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.049           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.669           ms/op
ClientPb.getUser                        sample  174923   5.490 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.980           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.905           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.108           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.938           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.835           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.408           ms/op
ClientPb.listUser                       sample  153005   6.269 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.999           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.882           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.020           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.241           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.140           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.330           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.063           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.717           ms/op
