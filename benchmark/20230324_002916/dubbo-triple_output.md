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
# Warmup Iteration   1: 2.510 ops/ms
# Warmup Iteration   2: 5.757 ops/ms
# Warmup Iteration   3: 9.926 ops/ms
Iteration   1: 9.852 ops/ms
Iteration   2: 10.273 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.160 ±(99.9%) 4.917 ops/ms [Average]
  (min, avg, max) = (9.852, 10.160, 10.354), stdev = 0.270
  CI (99.9%): [5.243, 15.077] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.931 ops/ms
# Warmup Iteration   2: 9.886 ops/ms
# Warmup Iteration   3: 10.336 ops/ms
Iteration   1: 10.741 ops/ms
Iteration   2: 10.768 ops/ms
Iteration   3: 10.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.557 ±(99.9%) 6.239 ops/ms [Average]
  (min, avg, max) = (10.162, 10.557, 10.768), stdev = 0.342
  CI (99.9%): [4.318, 16.796] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.614 ops/ms
# Warmup Iteration   2: 9.472 ops/ms
# Warmup Iteration   3: 10.076 ops/ms
Iteration   1: 10.091 ops/ms
Iteration   2: 10.584 ops/ms
Iteration   3: 9.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.110 ±(99.9%) 8.480 ops/ms [Average]
  (min, avg, max) = (9.655, 10.110, 10.584), stdev = 0.465
  CI (99.9%): [1.630, 18.590] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.523 ops/ms
# Warmup Iteration   2: 8.087 ops/ms
# Warmup Iteration   3: 8.506 ops/ms
Iteration   1: 8.752 ops/ms
Iteration   2: 8.748 ops/ms
Iteration   3: 8.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.756 ±(99.9%) 0.204 ops/ms [Average]
  (min, avg, max) = (8.748, 8.756, 8.769), stdev = 0.011
  CI (99.9%): [8.552, 8.960] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.765 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.007 ms/op
Iteration   1: 3.246 ±(99.9%) 0.006 ms/op
Iteration   2: 3.114 ±(99.9%) 0.003 ms/op
Iteration   3: 3.142 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.167 ±(99.9%) 1.276 ms/op [Average]
  (min, avg, max) = (3.114, 3.167, 3.246), stdev = 0.070
  CI (99.9%): [1.892, 4.443] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.177 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.006 ms/op
Iteration   1: 3.164 ±(99.9%) 0.008 ms/op
Iteration   2: 3.077 ±(99.9%) 0.009 ms/op
Iteration   3: 3.079 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.107 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (3.077, 3.107, 3.164), stdev = 0.050
  CI (99.9%): [2.197, 4.017] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.728 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.002 ms/op
Iteration   1: 3.185 ±(99.9%) 0.003 ms/op
Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
Iteration   3: 3.129 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.118 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (3.042, 3.118, 3.185), stdev = 0.072
  CI (99.9%): [1.809, 4.427] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.551 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.005 ms/op
Iteration   1: 3.673 ±(99.9%) 0.011 ms/op
Iteration   2: 3.727 ±(99.9%) 0.007 ms/op
Iteration   3: 3.682 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.694 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (3.673, 3.694, 3.727), stdev = 0.029
  CI (99.9%): [3.163, 4.225] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.384 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.009 ms/op
Iteration   1: 3.307 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  13.578 ms/op
                 createUser·p0.9999: 29.458 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.438 ms/op
                 createUser·p0.999:  12.953 ms/op
                 createUser·p0.9999: 23.322 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   3: 3.120 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.631 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  16.145 ms/op
                 createUser·p0.9999: 26.591 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300739
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13696 
    [ 2.500,  5.000) = 279762 
    [ 5.000,  7.500) = 6405 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     16.048 ms/op
     p(99.9900) =     28.309 ms/op
     p(99.9990) =     29.751 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.072 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
Iteration   1: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 18.845 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.310 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  12.912 ms/op
                 existUser·p0.9999: 23.344 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.139 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.549 ms/op
                 existUser·p0.9999: 30.790 ms/op
                 existUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310034
  mean =      3.095 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24526 
    [ 2.500,  5.000) = 280500 
    [ 5.000,  7.500) = 4203 
    [ 7.500, 10.000) = 322 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     31.192 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.471 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.010 ms/op
Iteration   1: 3.392 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  15.456 ms/op
                 getUser·p0.9999: 18.126 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   2: 3.254 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.414 ms/op
                 getUser·p0.9999: 21.993 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  11.215 ms/op
                 getUser·p0.9999: 19.770 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289305
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19813 
    [ 2.500,  5.000) = 261522 
    [ 5.000,  7.500) = 7076 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     15.068 ms/op
     p(99.9900) =     20.683 ms/op
     p(99.9990) =     22.326 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.920 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.011 ms/op
Iteration   1: 3.671 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.574 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 20.489 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 3.716 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 3.604 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.715 ms/op
                 listUser·p0.95:   3.781 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  11.911 ms/op
                 listUser·p0.9999: 13.189 ms/op
                 listUser·p1.00:   13.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261913
  mean =      3.663 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 255171 
    [ 5.000,  7.500) = 5264 
    [ 7.500, 10.000) = 793 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     19.589 ms/op
     p(99.9990) =     20.961 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.160 ± 4.917  ops/ms
ClientPb.existUser                       thrpt       3  10.557 ± 6.239  ops/ms
ClientPb.getUser                         thrpt       3  10.110 ± 8.480  ops/ms
ClientPb.listUser                        thrpt       3   8.756 ± 0.204  ops/ms
ClientPb.createUser                       avgt       3   3.167 ± 1.276   ms/op
ClientPb.existUser                        avgt       3   3.107 ± 0.910   ms/op
ClientPb.getUser                          avgt       3   3.118 ± 1.309   ms/op
ClientPb.listUser                         avgt       3   3.694 ± 0.531   ms/op
ClientPb.createUser                     sample  300739   3.192 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.638           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.048           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.309           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.819           ms/op
ClientPb.existUser                      sample  310034   3.095 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.310           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.416           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.943           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.508           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.556           ms/op
ClientPb.getUser                        sample  289305   3.317 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.753           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.068           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.683           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.413           ms/op
ClientPb.listUser                       sample  261913   3.663 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.733           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.141           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.304           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.589           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.234           ms/op
