# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.565 ops/ms
# Warmup Iteration   2: 6.237 ops/ms
# Warmup Iteration   3: 9.094 ops/ms
Iteration   1: 10.103 ops/ms
Iteration   2: 9.467 ops/ms
Iteration   3: 10.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.958 ±(99.9%) 7.986 ops/ms [Average]
  (min, avg, max) = (9.467, 9.958, 10.306), stdev = 0.438
  CI (99.9%): [1.972, 17.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.658 ops/ms
# Warmup Iteration   2: 9.412 ops/ms
# Warmup Iteration   3: 10.258 ops/ms
Iteration   1: 10.467 ops/ms
Iteration   2: 10.678 ops/ms
Iteration   3: 10.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.527 ±(99.9%) 2.398 ops/ms [Average]
  (min, avg, max) = (10.437, 10.527, 10.678), stdev = 0.131
  CI (99.9%): [8.129, 12.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.916 ops/ms
# Warmup Iteration   2: 8.455 ops/ms
# Warmup Iteration   3: 9.848 ops/ms
Iteration   1: 10.078 ops/ms
Iteration   2: 10.119 ops/ms
Iteration   3: 10.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.094 ±(99.9%) 0.406 ops/ms [Average]
  (min, avg, max) = (10.078, 10.094, 10.119), stdev = 0.022
  CI (99.9%): [9.688, 10.500] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.527 ops/ms
# Warmup Iteration   2: 7.691 ops/ms
# Warmup Iteration   3: 8.189 ops/ms
Iteration   1: 8.342 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.461 ±(99.9%) 3.365 ops/ms [Average]
  (min, avg, max) = (8.342, 8.461, 8.674), stdev = 0.184
  CI (99.9%): [5.096, 11.826] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.103 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.005 ms/op
Iteration   1: 3.384 ±(99.9%) 0.006 ms/op
Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
Iteration   3: 3.163 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.232 ±(99.9%) 2.395 ms/op [Average]
  (min, avg, max) = (3.150, 3.232, 3.384), stdev = 0.131
  CI (99.9%): [0.837, 5.628] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.005 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.005 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
Iteration   3: 3.127 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.082 ±(99.9%) 1.050 ms/op [Average]
  (min, avg, max) = (3.017, 3.082, 3.127), stdev = 0.058
  CI (99.9%): [2.032, 4.132] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.702 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.004 ms/op
Iteration   1: 3.213 ±(99.9%) 0.006 ms/op
Iteration   2: 3.205 ±(99.9%) 0.003 ms/op
Iteration   3: 3.188 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.202 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (3.188, 3.202, 3.213), stdev = 0.013
  CI (99.9%): [2.971, 3.433] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.717 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.005 ms/op
Iteration   1: 3.747 ±(99.9%) 0.007 ms/op
Iteration   2: 3.789 ±(99.9%) 0.004 ms/op
Iteration   3: 3.665 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.734 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (3.665, 3.734, 3.789), stdev = 0.063
  CI (99.9%): [2.586, 4.882] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.069 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.008 ms/op
Iteration   1: 3.247 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 25.657 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   2: 3.206 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  19.929 ms/op
                 createUser·p0.9999: 24.024 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   3: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.821 ms/op
                 createUser·p0.999:  13.820 ms/op
                 createUser·p0.9999: 18.345 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299086
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19590 
    [ 2.500,  5.000) = 273432 
    [ 5.000,  7.500) = 5033 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     16.660 ms/op
     p(99.9900) =     24.972 ms/op
     p(99.9990) =     25.922 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.261 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
Iteration   1: 3.283 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  9.873 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  12.656 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   3: 3.113 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   4.891 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 24.633 ms/op
                 existUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299626
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31799 
    [ 2.500,  5.000) = 262743 
    [ 5.000,  7.500) = 4331 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     12.655 ms/op
     p(99.9900) =     23.629 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.688 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.206 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 26.935 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.700 ms/op
                 getUser·p0.999:  9.322 ms/op
                 getUser·p0.9999: 22.097 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 20.744 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298706
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10852 
    [ 2.500,  5.000) = 281059 
    [ 5.000,  7.500) = 5778 
    [ 7.500, 10.000) = 626 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     17.540 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     26.956 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.098 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.012 ms/op
Iteration   1: 3.847 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   5.049 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  16.085 ms/op
                 listUser·p0.9999: 21.576 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   2: 3.761 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.567 ms/op
                 listUser·p0.999:  12.304 ms/op
                 listUser·p0.9999: 14.590 ms/op
                 listUser·p1.00:   15.811 ms/op

Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.622 ms/op
                 listUser·p0.999:  14.347 ms/op
                 listUser·p0.9999: 20.650 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252220
  mean =      3.804 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 242876 
    [ 5.000,  7.500) = 6928 
    [ 7.500, 10.000) = 1565 
    [10.000, 12.500) = 373 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     14.201 ms/op
     p(99.9900) =     20.768 ms/op
     p(99.9990) =     22.673 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.958 ± 7.986  ops/ms
ClientPb.existUser                       thrpt       3  10.527 ± 2.398  ops/ms
ClientPb.getUser                         thrpt       3  10.094 ± 0.406  ops/ms
ClientPb.listUser                        thrpt       3   8.461 ± 3.365  ops/ms
ClientPb.createUser                       avgt       3   3.232 ± 2.395   ms/op
ClientPb.existUser                        avgt       3   3.082 ± 1.050   ms/op
ClientPb.getUser                          avgt       3   3.202 ± 0.231   ms/op
ClientPb.listUser                         avgt       3   3.734 ± 1.148   ms/op
ClientPb.createUser                     sample  299086   3.208 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.873           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.660           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.972           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.706           ms/op
ClientPb.existUser                      sample  299626   3.202 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.155           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.655           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.629           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.149           ms/op
ClientPb.getUser                        sample  298706   3.211 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.174           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.568           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.890           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.540           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.182           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.508           ms/op
ClientPb.listUser                       sample  252220   3.804 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.403           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.201           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.768           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.003           ms/op
