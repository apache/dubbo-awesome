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
# Warmup Iteration   1: 2.200 ops/ms
# Warmup Iteration   2: 5.182 ops/ms
# Warmup Iteration   3: 8.331 ops/ms
Iteration   1: 9.180 ops/ms
Iteration   2: 9.228 ops/ms
Iteration   3: 9.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.220 ±(99.9%) 0.683 ops/ms [Average]
  (min, avg, max) = (9.180, 9.220, 9.253), stdev = 0.037
  CI (99.9%): [8.537, 9.903] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.010 ops/ms
# Warmup Iteration   2: 8.703 ops/ms
# Warmup Iteration   3: 9.619 ops/ms
Iteration   1: 9.762 ops/ms
Iteration   2: 9.512 ops/ms
Iteration   3: 9.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.686 ±(99.9%) 2.749 ops/ms [Average]
  (min, avg, max) = (9.512, 9.686, 9.783), stdev = 0.151
  CI (99.9%): [6.937, 12.435] (assumes normal distribution)


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
# Warmup Iteration   1: 3.024 ops/ms
# Warmup Iteration   2: 8.441 ops/ms
# Warmup Iteration   3: 8.625 ops/ms
Iteration   1: 9.324 ops/ms
Iteration   2: 9.110 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.222 ±(99.9%) 1.954 ops/ms [Average]
  (min, avg, max) = (9.110, 9.222, 9.324), stdev = 0.107
  CI (99.9%): [7.267, 11.176] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.953 ops/ms
# Warmup Iteration   2: 7.049 ops/ms
# Warmup Iteration   3: 7.579 ops/ms
Iteration   1: 7.894 ops/ms
Iteration   2: 7.984 ops/ms
Iteration   3: 7.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.896 ±(99.9%) 1.585 ops/ms [Average]
  (min, avg, max) = (7.811, 7.896, 7.984), stdev = 0.087
  CI (99.9%): [6.312, 9.481] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.112 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
Iteration   1: 3.478 ±(99.9%) 0.008 ms/op
Iteration   2: 3.402 ±(99.9%) 0.011 ms/op
Iteration   3: 3.431 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.437 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.402, 3.437, 3.478), stdev = 0.038
  CI (99.9%): [2.742, 4.132] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.773 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.005 ms/op
Iteration   1: 3.489 ±(99.9%) 0.003 ms/op
Iteration   2: 3.401 ±(99.9%) 0.006 ms/op
Iteration   3: 3.357 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.416 ±(99.9%) 1.219 ms/op [Average]
  (min, avg, max) = (3.357, 3.416, 3.489), stdev = 0.067
  CI (99.9%): [2.196, 4.635] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.574 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.003 ms/op
Iteration   1: 3.496 ±(99.9%) 0.004 ms/op
Iteration   2: 3.494 ±(99.9%) 0.006 ms/op
Iteration   3: 3.511 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.500 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (3.494, 3.500, 3.511), stdev = 0.009
  CI (99.9%): [3.330, 3.670] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.740 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.010 ms/op
Iteration   1: 4.065 ±(99.9%) 0.008 ms/op
Iteration   2: 4.139 ±(99.9%) 0.001 ms/op
Iteration   3: 4.034 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.079 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (4.034, 4.079, 4.139), stdev = 0.054
  CI (99.9%): [3.091, 5.068] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.065 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.011 ms/op
Iteration   1: 3.621 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   6.259 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  19.097 ms/op
                 createUser·p0.9999: 21.607 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.516 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.413 ms/op
                 createUser·p0.999:  19.962 ms/op
                 createUser·p0.9999: 28.738 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   3: 3.607 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.691 ms/op
                 createUser·p0.999:  16.468 ms/op
                 createUser·p0.9999: 25.053 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267737
  mean =      3.581 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6420 
    [ 2.500,  5.000) = 249582 
    [ 5.000,  7.500) = 9425 
    [ 7.500, 10.000) = 1649 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     18.269 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     29.184 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.150 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.009 ms/op
Iteration   1: 3.426 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.621 ms/op
                 existUser·p0.999:  19.447 ms/op
                 existUser·p0.9999: 23.189 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.397 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  21.585 ms/op
                 existUser·p0.9999: 31.791 ms/op
                 existUser·p1.00:   32.768 ms/op

Iteration   3: 3.494 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 25.784 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278883
  mean =      3.439 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7273 
    [ 2.500,  5.000) = 260419 
    [ 5.000,  7.500) = 9577 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     30.380 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.313 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.012 ms/op
Iteration   1: 3.538 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 23.035 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   2: 3.402 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.909 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  22.049 ms/op
                 getUser·p0.9999: 26.109 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  19.865 ms/op
                 getUser·p0.9999: 32.042 ms/op
                 getUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274769
  mean =      3.491 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5833 
    [ 2.500,  5.000) = 259830 
    [ 5.000,  7.500) = 7590 
    [ 7.500, 10.000) = 1190 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.409 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     32.694 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.044 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.014 ms/op
Iteration   1: 4.134 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  22.760 ms/op
                 listUser·p0.9999: 26.845 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   2: 4.065 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  15.860 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 4.143 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   8.972 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 16.733 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233204
  mean =      4.114 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 222258 
    [ 5.000,  7.500) = 7484 
    [ 7.500, 10.000) = 2412 
    [10.000, 12.500) = 640 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.786 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     15.906 ms/op
     p(99.9900) =     25.528 ms/op
     p(99.9990) =     27.405 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.220 ± 0.683  ops/ms
ClientPb.existUser                       thrpt       3   9.686 ± 2.749  ops/ms
ClientPb.getUser                         thrpt       3   9.222 ± 1.954  ops/ms
ClientPb.listUser                        thrpt       3   7.896 ± 1.585  ops/ms
ClientPb.createUser                       avgt       3   3.437 ± 0.695   ms/op
ClientPb.existUser                        avgt       3   3.416 ± 1.219   ms/op
ClientPb.getUser                          avgt       3   3.500 ± 0.170   ms/op
ClientPb.listUser                         avgt       3   4.079 ± 0.989   ms/op
ClientPb.createUser                     sample  267737   3.581 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.737           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.165           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.360           ms/op
ClientPb.existUser                      sample  278883   3.439 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.239           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.588           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.073           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.380           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.768           ms/op
ClientPb.getUser                        sample  274769   3.491 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.221           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.409           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.713           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.950           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.194           ms/op
ClientPb.listUser                       sample  233204   4.114 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.906           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.528           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.623           ms/op
