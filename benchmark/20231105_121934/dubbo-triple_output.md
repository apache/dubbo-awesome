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
# Warmup Iteration   1: 1.000 ops/ms
# Warmup Iteration   2: 2.153 ops/ms
# Warmup Iteration   3: 4.766 ops/ms
Iteration   1: 5.074 ops/ms
Iteration   2: 5.318 ops/ms
Iteration   3: 5.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.285 ±(99.9%) 3.578 ops/ms [Average]
  (min, avg, max) = (5.074, 5.285, 5.462), stdev = 0.196
  CI (99.9%): [1.707, 8.862] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.576 ops/ms
# Warmup Iteration   2: 3.920 ops/ms
# Warmup Iteration   3: 5.436 ops/ms
Iteration   1: 5.600 ops/ms
Iteration   2: 5.668 ops/ms
Iteration   3: 5.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.588 ±(99.9%) 1.565 ops/ms [Average]
  (min, avg, max) = (5.497, 5.588, 5.668), stdev = 0.086
  CI (99.9%): [4.023, 7.154] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.251 ops/ms
# Warmup Iteration   2: 3.813 ops/ms
# Warmup Iteration   3: 5.282 ops/ms
Iteration   1: 5.248 ops/ms
Iteration   2: 5.423 ops/ms
Iteration   3: 5.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.375 ±(99.9%) 2.021 ops/ms [Average]
  (min, avg, max) = (5.248, 5.375, 5.454), stdev = 0.111
  CI (99.9%): [3.354, 7.396] (assumes normal distribution)


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
# Warmup Iteration   1: 1.268 ops/ms
# Warmup Iteration   2: 3.098 ops/ms
# Warmup Iteration   3: 4.328 ops/ms
Iteration   1: 4.471 ops/ms
Iteration   2: 4.583 ops/ms
Iteration   3: 4.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.539 ±(99.9%) 1.087 ops/ms [Average]
  (min, avg, max) = (4.471, 4.539, 4.583), stdev = 0.060
  CI (99.9%): [3.452, 5.626] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 20.270 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 7.133 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.350 ±(99.9%) 0.010 ms/op
Iteration   1: 6.171 ±(99.9%) 0.013 ms/op
Iteration   2: 5.755 ±(99.9%) 0.014 ms/op
Iteration   3: 6.003 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.977 ±(99.9%) 3.816 ms/op [Average]
  (min, avg, max) = (5.755, 5.977, 6.171), stdev = 0.209
  CI (99.9%): [2.161, 9.792] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.606 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.539 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.928 ±(99.9%) 0.006 ms/op
Iteration   1: 5.923 ±(99.9%) 0.008 ms/op
Iteration   2: 5.701 ±(99.9%) 0.009 ms/op
Iteration   3: 5.808 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.811 ±(99.9%) 2.024 ms/op [Average]
  (min, avg, max) = (5.701, 5.811, 5.923), stdev = 0.111
  CI (99.9%): [3.787, 7.835] (assumes normal distribution)


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
# Warmup Iteration   1: 19.966 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 7.760 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.123 ±(99.9%) 0.007 ms/op
Iteration   1: 6.071 ±(99.9%) 0.011 ms/op
Iteration   2: 6.075 ±(99.9%) 0.009 ms/op
Iteration   3: 6.357 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.168 ±(99.9%) 2.993 ms/op [Average]
  (min, avg, max) = (6.071, 6.168, 6.357), stdev = 0.164
  CI (99.9%): [3.175, 9.161] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 23.463 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 8.976 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 7.052 ±(99.9%) 0.011 ms/op
Iteration   1: 7.092 ±(99.9%) 0.014 ms/op
Iteration   2: 7.013 ±(99.9%) 0.011 ms/op
Iteration   3: 6.840 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.982 ±(99.9%) 2.358 ms/op [Average]
  (min, avg, max) = (6.840, 6.982, 7.092), stdev = 0.129
  CI (99.9%): [4.623, 9.340] (assumes normal distribution)


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
# Warmup Iteration   1: 20.666 ±(99.9%) 0.425 ms/op
# Warmup Iteration   2: 7.371 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.766 ±(99.9%) 0.039 ms/op
Iteration   1: 6.087 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.441 ms/op
                 createUser·p0.50:   5.571 ms/op
                 createUser·p0.90:   8.118 ms/op
                 createUser·p0.95:   9.486 ms/op
                 createUser·p0.99:   13.025 ms/op
                 createUser·p0.999:  25.305 ms/op
                 createUser·p0.9999: 35.666 ms/op
                 createUser·p1.00:   37.028 ms/op

Iteration   2: 5.879 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.421 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.594 ms/op
                 createUser·p0.95:   8.880 ms/op
                 createUser·p0.99:   12.435 ms/op
                 createUser·p0.999:  27.644 ms/op
                 createUser·p0.9999: 32.987 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   3: 6.037 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   2.605 ms/op
                 createUser·p0.50:   5.554 ms/op
                 createUser·p0.90:   7.848 ms/op
                 createUser·p0.95:   9.241 ms/op
                 createUser·p0.99:   13.140 ms/op
                 createUser·p0.999:  32.476 ms/op
                 createUser·p0.9999: 37.533 ms/op
                 createUser·p1.00:   40.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 159858
  mean =      6.000 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 37102 
    [ 5.000, 10.000) = 117306 
    [10.000, 15.000) = 4791 
    [15.000, 20.000) = 391 
    [20.000, 25.000) = 46 
    [25.000, 30.000) = 73 
    [30.000, 35.000) = 108 
    [35.000, 40.000) = 39 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.421 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.856 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     12.845 ms/op
     p(99.9000) =     29.529 ms/op
     p(99.9900) =     37.290 ms/op
     p(99.9990) =     40.108 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


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
# Warmup Iteration   1: 19.760 ±(99.9%) 0.353 ms/op
# Warmup Iteration   2: 6.848 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.323 ±(99.9%) 0.030 ms/op
Iteration   1: 5.804 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   5.439 ms/op
                 existUser·p0.90:   7.381 ms/op
                 existUser·p0.95:   8.421 ms/op
                 existUser·p0.99:   12.124 ms/op
                 existUser·p0.999:  27.584 ms/op
                 existUser·p0.9999: 30.292 ms/op
                 existUser·p1.00:   30.966 ms/op

Iteration   2: 5.677 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.511 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   7.094 ms/op
                 existUser·p0.95:   8.169 ms/op
                 existUser·p0.99:   11.665 ms/op
                 existUser·p0.999:  30.869 ms/op
                 existUser·p0.9999: 35.610 ms/op
                 existUser·p1.00:   36.307 ms/op

Iteration   3: 5.603 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.494 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   6.955 ms/op
                 existUser·p0.95:   7.946 ms/op
                 existUser·p0.99:   11.780 ms/op
                 existUser·p0.999:  18.317 ms/op
                 existUser·p0.9999: 31.766 ms/op
                 existUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168564
  mean =      5.693 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 51109 
    [ 5.000,  7.500) = 104145 
    [ 7.500, 10.000) = 9852 
    [10.000, 12.500) = 2141 
    [12.500, 15.000) = 826 
    [15.000, 17.500) = 271 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 65 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.182 ms/op
     p(99.0000) =     11.911 ms/op
     p(99.9000) =     25.016 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     35.947 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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
# Warmup Iteration   1: 19.233 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 7.013 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.504 ±(99.9%) 0.029 ms/op
Iteration   1: 6.289 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.703 ms/op
                 getUser·p0.50:   5.693 ms/op
                 getUser·p0.90:   8.421 ms/op
                 getUser·p0.95:   10.011 ms/op
                 getUser·p0.99:   14.409 ms/op
                 getUser·p0.999:  25.826 ms/op
                 getUser·p0.9999: 30.624 ms/op
                 getUser·p1.00:   31.064 ms/op

Iteration   2: 6.296 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   5.857 ms/op
                 getUser·p0.90:   8.339 ms/op
                 getUser·p0.95:   9.617 ms/op
                 getUser·p0.99:   13.074 ms/op
                 getUser·p0.999:  26.058 ms/op
                 getUser·p0.9999: 28.823 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   3: 5.925 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.769 ms/op
                 getUser·p0.50:   5.538 ms/op
                 getUser·p0.90:   7.584 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   11.772 ms/op
                 getUser·p0.999:  30.969 ms/op
                 getUser·p0.9999: 33.896 ms/op
                 getUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 155567
  mean =      6.165 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 28050 
    [ 5.000,  7.500) = 105829 
    [ 7.500, 10.000) = 15783 
    [10.000, 12.500) = 4004 
    [12.500, 15.000) = 1166 
    [15.000, 17.500) = 285 
    [17.500, 20.000) = 169 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      8.118 ms/op
     p(95.0000) =      9.470 ms/op
     p(99.0000) =     13.091 ms/op
     p(99.9000) =     26.261 ms/op
     p(99.9900) =     33.045 ms/op
     p(99.9990) =     35.957 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 19.633 ±(99.9%) 0.358 ms/op
# Warmup Iteration   2: 9.737 ±(99.9%) 0.079 ms/op
# Warmup Iteration   3: 7.659 ±(99.9%) 0.039 ms/op
Iteration   1: 7.107 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   6.644 ms/op
                 listUser·p0.90:   8.995 ms/op
                 listUser·p0.95:   10.371 ms/op
                 listUser·p0.99:   14.013 ms/op
                 listUser·p0.999:  32.118 ms/op
                 listUser·p0.9999: 35.128 ms/op
                 listUser·p1.00:   35.783 ms/op

Iteration   2: 6.969 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.774 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   8.798 ms/op
                 listUser·p0.95:   10.338 ms/op
                 listUser·p0.99:   14.473 ms/op
                 listUser·p0.999:  33.900 ms/op
                 listUser·p0.9999: 41.697 ms/op
                 listUser·p1.00:   42.336 ms/op

Iteration   3: 7.149 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   2.802 ms/op
                 listUser·p0.50:   6.603 ms/op
                 listUser·p0.90:   9.142 ms/op
                 listUser·p0.95:   10.682 ms/op
                 listUser·p0.99:   15.487 ms/op
                 listUser·p0.999:  31.694 ms/op
                 listUser·p0.9999: 42.424 ms/op
                 listUser·p1.00:   44.958 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 135618
  mean =      7.074 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2096 
    [ 5.000, 10.000) = 125055 
    [10.000, 15.000) = 7195 
    [15.000, 20.000) = 841 
    [20.000, 25.000) = 102 
    [25.000, 30.000) = 77 
    [30.000, 35.000) = 178 
    [35.000, 40.000) = 50 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      6.554 ms/op
     p(90.0000) =      8.978 ms/op
     p(95.0000) =     10.486 ms/op
     p(99.0000) =     14.762 ms/op
     p(99.9000) =     32.740 ms/op
     p(99.9900) =     41.185 ms/op
     p(99.9990) =     44.794 ms/op
     p(99.9999) =     44.958 ms/op
    p(100.0000) =     44.958 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.285 ± 3.578  ops/ms
ClientPb.existUser                       thrpt       3   5.588 ± 1.565  ops/ms
ClientPb.getUser                         thrpt       3   5.375 ± 2.021  ops/ms
ClientPb.listUser                        thrpt       3   4.539 ± 1.087  ops/ms
ClientPb.createUser                       avgt       3   5.977 ± 3.816   ms/op
ClientPb.existUser                        avgt       3   5.811 ± 2.024   ms/op
ClientPb.getUser                          avgt       3   6.168 ± 2.993   ms/op
ClientPb.listUser                         avgt       3   6.982 ± 2.358   ms/op
ClientPb.createUser                     sample  159858   6.000 ± 0.016   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.856           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.224           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.845           ms/op
ClientPb.createUser:createUser·p0.999   sample          29.529           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.290           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.108           ms/op
ClientPb.existUser                      sample  168564   5.693 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.741           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.182           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.911           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.016           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.260           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.307           ms/op
ClientPb.getUser                        sample  155567   6.165 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.932           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.118           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.470           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.091           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.261           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.045           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  135618   7.074 ± 0.019   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.210           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.554           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.978           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.486           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.762           ms/op
ClientPb.listUser:listUser·p0.999       sample          32.740           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.185           ms/op
ClientPb.listUser:listUser·p1.00        sample          44.958           ms/op
