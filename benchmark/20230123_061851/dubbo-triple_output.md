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
# Warmup Iteration   1: 1.098 ops/ms
# Warmup Iteration   2: 2.468 ops/ms
# Warmup Iteration   3: 5.615 ops/ms
Iteration   1: 5.862 ops/ms
Iteration   2: 6.057 ops/ms
Iteration   3: 6.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.040 ±(99.9%) 3.109 ops/ms [Average]
  (min, avg, max) = (5.862, 6.040, 6.201), stdev = 0.170
  CI (99.9%): [2.931, 9.149] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.699 ops/ms
# Warmup Iteration   2: 5.415 ops/ms
# Warmup Iteration   3: 6.276 ops/ms
Iteration   1: 6.436 ops/ms
Iteration   2: 6.364 ops/ms
Iteration   3: 6.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.395 ±(99.9%) 0.672 ops/ms [Average]
  (min, avg, max) = (6.364, 6.395, 6.436), stdev = 0.037
  CI (99.9%): [5.723, 7.067] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.718 ops/ms
# Warmup Iteration   2: 4.751 ops/ms
# Warmup Iteration   3: 6.070 ops/ms
Iteration   1: 6.108 ops/ms
Iteration   2: 6.272 ops/ms
Iteration   3: 6.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.233 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (6.108, 6.233, 6.320), stdev = 0.111
  CI (99.9%): [4.200, 8.266] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.604 ops/ms
# Warmup Iteration   2: 4.713 ops/ms
# Warmup Iteration   3: 5.184 ops/ms
Iteration   1: 5.454 ops/ms
Iteration   2: 5.325 ops/ms
Iteration   3: 5.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.464 ±(99.9%) 2.632 ops/ms [Average]
  (min, avg, max) = (5.325, 5.464, 5.613), stdev = 0.144
  CI (99.9%): [2.832, 8.095] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 16.936 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.349 ±(99.9%) 0.013 ms/op
Iteration   1: 5.207 ±(99.9%) 0.012 ms/op
Iteration   2: 5.109 ±(99.9%) 0.012 ms/op
Iteration   3: 4.998 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.105 ±(99.9%) 1.907 ms/op [Average]
  (min, avg, max) = (4.998, 5.105, 5.207), stdev = 0.105
  CI (99.9%): [3.198, 7.011] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.957 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.577 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.187 ±(99.9%) 0.007 ms/op
Iteration   1: 4.941 ±(99.9%) 0.009 ms/op
Iteration   2: 5.109 ±(99.9%) 0.006 ms/op
Iteration   3: 4.893 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.981 ±(99.9%) 2.068 ms/op [Average]
  (min, avg, max) = (4.893, 4.981, 5.109), stdev = 0.113
  CI (99.9%): [2.914, 7.049] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.348 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.786 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.256 ±(99.9%) 0.012 ms/op
Iteration   1: 5.194 ±(99.9%) 0.012 ms/op
Iteration   2: 5.166 ±(99.9%) 0.012 ms/op
Iteration   3: 5.098 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.153 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (5.098, 5.153, 5.194), stdev = 0.049
  CI (99.9%): [4.256, 6.050] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.686 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.817 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.848 ±(99.9%) 0.019 ms/op
Iteration   1: 6.039 ±(99.9%) 0.013 ms/op
Iteration   2: 5.839 ±(99.9%) 0.011 ms/op
Iteration   3: 6.014 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.964 ±(99.9%) 1.985 ms/op [Average]
  (min, avg, max) = (5.839, 5.964, 6.039), stdev = 0.109
  CI (99.9%): [3.979, 7.949] (assumes normal distribution)


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
# Warmup Iteration   1: 16.432 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 8.182 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 5.789 ±(99.9%) 0.025 ms/op
Iteration   1: 5.395 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.603 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   9.634 ms/op
                 createUser·p0.999:  23.749 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   2: 5.270 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.102 ms/op
                 createUser·p0.99:   9.785 ms/op
                 createUser·p0.999:  25.109 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   29.917 ms/op

Iteration   3: 5.219 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.275 ms/op
                 createUser·p0.95:   6.783 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  25.747 ms/op
                 createUser·p0.9999: 29.393 ms/op
                 createUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181258
  mean =      5.294 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 86222 
    [ 5.000,  7.500) = 88014 
    [ 7.500, 10.000) = 5611 
    [10.000, 12.500) = 828 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     24.557 ms/op
     p(99.9900) =     29.258 ms/op
     p(99.9990) =     30.296 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 17.432 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.236 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.120 ±(99.9%) 0.018 ms/op
Iteration   1: 4.954 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.187 ms/op
                 existUser·p0.50:   4.612 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  14.295 ms/op
                 existUser·p0.9999: 24.251 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 4.991 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   6.070 ms/op
                 existUser·p0.95:   6.783 ms/op
                 existUser·p0.99:   10.289 ms/op
                 existUser·p0.999:  23.364 ms/op
                 existUser·p0.9999: 27.499 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   3: 4.906 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.939 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   5.792 ms/op
                 existUser·p0.95:   6.611 ms/op
                 existUser·p0.99:   9.552 ms/op
                 existUser·p0.999:  18.297 ms/op
                 existUser·p0.9999: 29.131 ms/op
                 existUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193731
  mean =      4.950 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 138739 
    [ 5.000,  7.500) = 48459 
    [ 7.500, 10.000) = 4658 
    [10.000, 12.500) = 1226 
    [12.500, 15.000) = 369 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.939 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      6.005 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     16.747 ms/op
     p(99.9900) =     28.058 ms/op
     p(99.9990) =     29.647 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 17.021 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.235 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.381 ±(99.9%) 0.021 ms/op
Iteration   1: 5.463 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   8.405 ms/op
                 getUser·p0.99:   12.583 ms/op
                 getUser·p0.999:  23.150 ms/op
                 getUser·p0.9999: 26.585 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 5.236 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.250 ms/op
                 getUser·p0.95:   6.988 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  23.523 ms/op
                 getUser·p0.9999: 33.019 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   3: 5.167 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.662 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.365 ms/op
                 getUser·p0.99:   10.208 ms/op
                 getUser·p0.999:  30.441 ms/op
                 getUser·p0.9999: 36.320 ms/op
                 getUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181642
  mean =      5.286 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 89558 
    [ 5.000,  7.500) = 84371 
    [ 7.500, 10.000) = 5108 
    [10.000, 12.500) = 1556 
    [12.500, 15.000) = 547 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     34.800 ms/op
     p(99.9990) =     36.712 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 17.532 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 7.278 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.353 ±(99.9%) 0.028 ms/op
Iteration   1: 6.094 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   7.754 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  26.412 ms/op
                 listUser·p0.9999: 28.787 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 6.169 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.753 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  25.133 ms/op
                 listUser·p0.9999: 29.485 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   3: 5.922 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.896 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  21.716 ms/op
                 listUser·p0.9999: 25.349 ms/op
                 listUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 158428
  mean =      6.060 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 11874 
    [ 5.000,  7.500) = 135825 
    [ 7.500, 10.000) = 8082 
    [10.000, 12.500) = 1652 
    [12.500, 15.000) = 453 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.890 ms/op
     p(50.0000) =      5.800 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     24.609 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     30.762 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.040 ± 3.109  ops/ms
ClientPb.existUser                       thrpt       3   6.395 ± 0.672  ops/ms
ClientPb.getUser                         thrpt       3   6.233 ± 2.033  ops/ms
ClientPb.listUser                        thrpt       3   5.464 ± 2.632  ops/ms
ClientPb.createUser                       avgt       3   5.105 ± 1.907   ms/op
ClientPb.existUser                        avgt       3   4.981 ± 2.068   ms/op
ClientPb.getUser                          avgt       3   5.153 ± 0.897   ms/op
ClientPb.listUser                         avgt       3   5.964 ± 1.985   ms/op
ClientPb.createUser                     sample  181258   5.294 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.501           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.046           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.406           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.119           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.437           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.557           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.258           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.228           ms/op
ClientPb.existUser                      sample  193731   4.950 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.939           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.840           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.880           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.747           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.058           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.015           ms/op
ClientPb.getUser                        sample  181642   5.286 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.702           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.078           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.928           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.362           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.800           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.766           ms/op
ClientPb.listUser                       sample  158428   6.060 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.890           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.995           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.190           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.609           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.279           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.490           ms/op
