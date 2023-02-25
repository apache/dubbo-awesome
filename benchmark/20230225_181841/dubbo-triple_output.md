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
# Warmup Iteration   1: 2.513 ops/ms
# Warmup Iteration   2: 6.880 ops/ms
# Warmup Iteration   3: 9.232 ops/ms
Iteration   1: 9.742 ops/ms
Iteration   2: 10.032 ops/ms
Iteration   3: 10.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.966 ±(99.9%) 3.628 ops/ms [Average]
  (min, avg, max) = (9.742, 9.966, 10.123), stdev = 0.199
  CI (99.9%): [6.338, 13.594] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ops/ms
# Warmup Iteration   2: 8.535 ops/ms
# Warmup Iteration   3: 10.283 ops/ms
Iteration   1: 10.615 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.689 ±(99.9%) 1.328 ops/ms [Average]
  (min, avg, max) = (10.615, 10.689, 10.761), stdev = 0.073
  CI (99.9%): [9.361, 12.017] (assumes normal distribution)


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
# Warmup Iteration   1: 4.022 ops/ms
# Warmup Iteration   2: 9.182 ops/ms
# Warmup Iteration   3: 9.602 ops/ms
Iteration   1: 10.280 ops/ms
Iteration   2: 10.139 ops/ms
Iteration   3: 9.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.028 ±(99.9%) 5.860 ops/ms [Average]
  (min, avg, max) = (9.667, 10.028, 10.280), stdev = 0.321
  CI (99.9%): [4.168, 15.888] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.134 ops/ms
# Warmup Iteration   2: 8.103 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 8.647 ops/ms
Iteration   2: 8.583 ops/ms
Iteration   3: 8.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.529 ±(99.9%) 2.791 ops/ms [Average]
  (min, avg, max) = (8.356, 8.529, 8.647), stdev = 0.153
  CI (99.9%): [5.738, 11.320] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.363 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.007 ms/op
Iteration   1: 3.219 ±(99.9%) 0.008 ms/op
Iteration   2: 3.172 ±(99.9%) 0.002 ms/op
Iteration   3: 3.222 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.204 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (3.172, 3.204, 3.222), stdev = 0.028
  CI (99.9%): [2.696, 3.712] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.698 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.205 ±(99.9%) 0.006 ms/op
Iteration   2: 3.127 ±(99.9%) 0.004 ms/op
Iteration   3: 2.958 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 2.309 ms/op [Average]
  (min, avg, max) = (2.958, 3.097, 3.205), stdev = 0.127
  CI (99.9%): [0.788, 5.405] (assumes normal distribution)


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
# Warmup Iteration   1: 8.204 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.003 ms/op
Iteration   1: 3.230 ±(99.9%) 0.001 ms/op
Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
Iteration   3: 3.154 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.162 ±(99.9%) 1.185 ms/op [Average]
  (min, avg, max) = (3.101, 3.162, 3.230), stdev = 0.065
  CI (99.9%): [1.977, 4.346] (assumes normal distribution)


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
# Warmup Iteration   1: 9.511 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.004 ms/op
Iteration   1: 3.616 ±(99.9%) 0.008 ms/op
Iteration   2: 3.601 ±(99.9%) 0.009 ms/op
Iteration   3: 3.768 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.661 ±(99.9%) 1.684 ms/op [Average]
  (min, avg, max) = (3.601, 3.661, 3.768), stdev = 0.092
  CI (99.9%): [1.978, 5.345] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.650 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.010 ms/op
Iteration   1: 3.051 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 19.841 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 21.919 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  16.450 ms/op
                 createUser·p0.9999: 23.782 ms/op
                 createUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305694
  mean =      3.139 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22285 
    [ 2.500,  5.000) = 278759 
    [ 5.000,  7.500) = 3757 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 207 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     17.377 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     24.214 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.659 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
Iteration   1: 3.021 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 19.885 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 3.003 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  8.454 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.994 ms/op
                 existUser·p0.9999: 23.304 ms/op
                 existUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314278
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16561 
    [ 2.500,  5.000) = 292310 
    [ 5.000,  7.500) = 4784 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     22.530 ms/op
     p(99.9990) =     23.864 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 7.756 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
Iteration   1: 3.164 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  13.890 ms/op
                 getUser·p0.9999: 18.014 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.458 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  9.227 ms/op
                 getUser·p0.9999: 25.756 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 3.145 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.785 ms/op
                 getUser·p0.999:  13.005 ms/op
                 getUser·p0.9999: 19.589 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305911
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12871 
    [ 2.500,  5.000) = 286404 
    [ 5.000,  7.500) = 5799 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     23.542 ms/op
     p(99.9990) =     25.885 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 10.180 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.012 ms/op
Iteration   1: 3.877 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  17.117 ms/op
                 listUser·p0.9999: 22.217 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  13.998 ms/op
                 listUser·p0.9999: 19.893 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   3: 3.717 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  12.484 ms/op
                 listUser·p0.9999: 14.867 ms/op
                 listUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253458
  mean =      3.790 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 242686 
    [ 5.000,  7.500) = 8405 
    [ 7.500, 10.000) = 1570 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     22.525 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.966 ± 3.628  ops/ms
ClientPb.existUser                       thrpt       3  10.689 ± 1.328  ops/ms
ClientPb.getUser                         thrpt       3  10.028 ± 5.860  ops/ms
ClientPb.listUser                        thrpt       3   8.529 ± 2.791  ops/ms
ClientPb.createUser                       avgt       3   3.204 ± 0.508   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 2.309   ms/op
ClientPb.getUser                          avgt       3   3.162 ± 1.185   ms/op
ClientPb.listUser                         avgt       3   3.661 ± 1.684   ms/op
ClientPb.createUser                     sample  305694   3.139 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.377           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.413           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.379           ms/op
ClientPb.existUser                      sample  314278   3.054 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.804           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.600           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.530           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.953           ms/op
ClientPb.getUser                        sample  305911   3.138 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.458           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.812           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.542           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.051           ms/op
ClientPb.listUser                       sample  253458   3.790 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.419           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.742           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.610           ms/op
