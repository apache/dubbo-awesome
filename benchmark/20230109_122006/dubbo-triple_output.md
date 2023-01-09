# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.046 ops/ms
# Warmup Iteration   2: 2.574 ops/ms
# Warmup Iteration   3: 5.114 ops/ms
Iteration   1: 5.833 ops/ms
Iteration   2: 6.095 ops/ms
Iteration   3: 6.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.002 ±(99.9%) 2.682 ops/ms [Average]
  (min, avg, max) = (5.833, 6.002, 6.095), stdev = 0.147
  CI (99.9%): [3.320, 8.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.651 ops/ms
# Warmup Iteration   2: 5.147 ops/ms
# Warmup Iteration   3: 6.314 ops/ms
Iteration   1: 6.248 ops/ms
Iteration   2: 6.379 ops/ms
Iteration   3: 6.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.371 ±(99.9%) 2.173 ops/ms [Average]
  (min, avg, max) = (6.248, 6.371, 6.486), stdev = 0.119
  CI (99.9%): [4.199, 8.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.587 ops/ms
# Warmup Iteration   2: 5.190 ops/ms
# Warmup Iteration   3: 5.918 ops/ms
Iteration   1: 5.722 ops/ms
Iteration   2: 6.051 ops/ms
Iteration   3: 6.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.977 ±(99.9%) 4.145 ops/ms [Average]
  (min, avg, max) = (5.722, 5.977, 6.158), stdev = 0.227
  CI (99.9%): [1.832, 10.122] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.629 ops/ms
# Warmup Iteration   2: 4.315 ops/ms
# Warmup Iteration   3: 5.438 ops/ms
Iteration   1: 5.324 ops/ms
Iteration   2: 5.373 ops/ms
Iteration   3: 5.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.359 ±(99.9%) 0.555 ops/ms [Average]
  (min, avg, max) = (5.324, 5.359, 5.380), stdev = 0.030
  CI (99.9%): [4.804, 5.915] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.034 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.748 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.433 ±(99.9%) 0.013 ms/op
Iteration   1: 5.210 ±(99.9%) 0.014 ms/op
Iteration   2: 5.208 ±(99.9%) 0.011 ms/op
Iteration   3: 5.050 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.156 ±(99.9%) 1.682 ms/op [Average]
  (min, avg, max) = (5.050, 5.156, 5.210), stdev = 0.092
  CI (99.9%): [3.474, 6.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.880 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 6.866 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.105 ±(99.9%) 0.010 ms/op
Iteration   1: 4.806 ±(99.9%) 0.016 ms/op
Iteration   2: 4.865 ±(99.9%) 0.016 ms/op
Iteration   3: 5.007 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.893 ±(99.9%) 1.886 ms/op [Average]
  (min, avg, max) = (4.806, 4.893, 5.007), stdev = 0.103
  CI (99.9%): [3.007, 6.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.637 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.075 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.543 ±(99.9%) 0.007 ms/op
Iteration   1: 5.128 ±(99.9%) 0.017 ms/op
Iteration   2: 5.218 ±(99.9%) 0.008 ms/op
Iteration   3: 5.306 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.217 ±(99.9%) 1.619 ms/op [Average]
  (min, avg, max) = (5.128, 5.217, 5.306), stdev = 0.089
  CI (99.9%): [3.598, 6.837] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.930 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 7.632 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.118 ±(99.9%) 0.013 ms/op
Iteration   1: 6.051 ±(99.9%) 0.010 ms/op
Iteration   2: 5.993 ±(99.9%) 0.019 ms/op
Iteration   3: 6.166 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.070 ±(99.9%) 1.600 ms/op [Average]
  (min, avg, max) = (5.993, 6.070, 6.166), stdev = 0.088
  CI (99.9%): [4.470, 7.670] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 19.533 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 6.935 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.497 ±(99.9%) 0.021 ms/op
Iteration   1: 5.274 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.331 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.357 ms/op
                 createUser·p0.95:   7.766 ms/op
                 createUser·p0.99:   10.420 ms/op
                 createUser·p0.999:  21.100 ms/op
                 createUser·p0.9999: 26.663 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   2: 5.165 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.923 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   7.168 ms/op
                 createUser·p0.99:   9.814 ms/op
                 createUser·p0.999:  22.381 ms/op
                 createUser·p0.9999: 25.461 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 5.162 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.441 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.234 ms/op
                 createUser·p0.95:   7.266 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  26.411 ms/op
                 createUser·p0.9999: 28.502 ms/op
                 createUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184426
  mean =      5.200 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 106517 
    [ 5.000,  7.500) = 69277 
    [ 7.500, 10.000) = 6644 
    [10.000, 12.500) = 1275 
    [12.500, 15.000) = 413 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.923 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     21.711 ms/op
     p(99.9900) =     28.297 ms/op
     p(99.9990) =     30.243 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.512 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 5.680 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.017 ms/op
Iteration   1: 4.999 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.040 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   7.078 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  22.130 ms/op
                 existUser·p0.9999: 26.378 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   2: 5.008 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.204 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   7.012 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  25.210 ms/op
                 existUser·p0.9999: 37.396 ms/op
                 existUser·p1.00:   37.945 ms/op

Iteration   3: 4.877 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.068 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   5.751 ms/op
                 existUser·p0.95:   6.562 ms/op
                 existUser·p0.99:   9.191 ms/op
                 existUser·p0.999:  18.531 ms/op
                 existUser·p0.9999: 40.071 ms/op
                 existUser·p1.00:   42.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193444
  mean =      4.960 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 134580 
    [ 5.000, 10.000) = 57251 
    [10.000, 15.000) = 1361 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 44 
    [25.000, 30.000) = 73 
    [30.000, 35.000) = 21 
    [35.000, 40.000) = 58 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.040 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     21.583 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     41.168 ms/op
     p(99.9999) =     42.271 ms/op
    p(100.0000) =     42.271 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.195 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 5.898 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.624 ±(99.9%) 0.024 ms/op
Iteration   1: 5.785 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   8.012 ms/op
                 getUser·p0.95:   9.470 ms/op
                 getUser·p0.99:   13.517 ms/op
                 getUser·p0.999:  24.610 ms/op
                 getUser·p0.9999: 31.195 ms/op
                 getUser·p1.00:   31.588 ms/op

Iteration   2: 5.899 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   8.290 ms/op
                 getUser·p0.95:   9.634 ms/op
                 getUser·p0.99:   13.953 ms/op
                 getUser·p0.999:  24.429 ms/op
                 getUser·p0.9999: 30.198 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   3: 5.515 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.040 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   7.012 ms/op
                 getUser·p0.95:   8.290 ms/op
                 getUser·p0.99:   11.583 ms/op
                 getUser·p0.999:  27.823 ms/op
                 getUser·p0.9999: 36.058 ms/op
                 getUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167540
  mean =      5.728 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 70988 
    [ 5.000,  7.500) = 77437 
    [ 7.500, 10.000) = 13233 
    [10.000, 12.500) = 3631 
    [12.500, 15.000) = 1532 
    [15.000, 17.500) = 385 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      7.774 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     13.173 ms/op
     p(99.9000) =     24.717 ms/op
     p(99.9900) =     35.209 ms/op
     p(99.9990) =     37.021 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.736 ±(99.9%) 0.354 ms/op
# Warmup Iteration   2: 8.262 ±(99.9%) 0.074 ms/op
# Warmup Iteration   3: 6.361 ±(99.9%) 0.028 ms/op
Iteration   1: 6.640 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.441 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   9.847 ms/op
                 listUser·p0.99:   12.894 ms/op
                 listUser·p0.999:  26.870 ms/op
                 listUser·p0.9999: 31.874 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   2: 6.298 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.993 ms/op
                 listUser·p0.50:   5.906 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.612 ms/op
                 listUser·p0.999:  29.524 ms/op
                 listUser·p0.9999: 38.005 ms/op
                 listUser·p1.00:   39.191 ms/op

Iteration   3: 6.424 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.043 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  24.778 ms/op
                 listUser·p0.9999: 30.803 ms/op
                 listUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148835
  mean =      6.451 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 5205 
    [ 5.000,  7.500) = 123556 
    [ 7.500, 10.000) = 15152 
    [10.000, 12.500) = 3648 
    [12.500, 15.000) = 670 
    [15.000, 17.500) = 276 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.993 ms/op
     p(50.0000) =      6.038 ms/op
     p(90.0000) =      8.020 ms/op
     p(95.0000) =      9.306 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     27.132 ms/op
     p(99.9900) =     34.480 ms/op
     p(99.9990) =     39.159 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.002 ± 2.682  ops/ms
ClientPb.existUser                       thrpt       3   6.371 ± 2.173  ops/ms
ClientPb.getUser                         thrpt       3   5.977 ± 4.145  ops/ms
ClientPb.listUser                        thrpt       3   5.359 ± 0.555  ops/ms
ClientPb.createUser                       avgt       3   5.156 ± 1.682   ms/op
ClientPb.existUser                        avgt       3   4.893 ± 1.886   ms/op
ClientPb.getUser                          avgt       3   5.217 ± 1.619   ms/op
ClientPb.listUser                         avgt       3   6.070 ± 1.600   ms/op
ClientPb.createUser                     sample  184426   5.200 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.923           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.283           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.373           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.158           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.711           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.297           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.409           ms/op
ClientPb.existUser                      sample  193444   4.960 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.040           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.021           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.930           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.667           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.583           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.271           ms/op
ClientPb.getUser                        sample  167540   5.728 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.841           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.774           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.224           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.173           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.717           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.209           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.552           ms/op
ClientPb.listUser                       sample  148835   6.451 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.993           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.038           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.020           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.206           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.132           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.480           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.191           ms/op
